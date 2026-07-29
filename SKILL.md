---
name: growth-design
description: Apply product-psychology frameworks from the Growth.Design course (BMAP behavior model, Psych framework, B.I.A.S. framework, customer journey mapping, humane-design ethics) when designing, reviewing, or improving any user-facing experience. Use this skill whenever the user wants to design or critique a UX flow, screen, onboarding, dialog, prompt, notification, empty state, paywall, or upgrade flow; asks "why aren't users doing X", "how can we improve conversion/activation/retention of this flow", or "review this screen/journey"; wants help preparing a design review or justifying a product decision; or mentions growth design, user psychology, friction, nudges, delight, or user motivation — even if they don't name a framework explicitly.
---

# Growth design

Frameworks for understanding why users behave the way they do and improving any experience — distilled from the Growth.Design product-psychology course. The through-line: every user has a **Psych level** (mental energy/willpower). Each interaction adds psych (motivation, clarity, delight) or drains it (friction, confusion, distrust). When psych hits zero, the user drops out.

## Which framework to use

| Situation | Framework | Reference |
|---|---|---|
| Users aren't doing the behavior you expect; you don't know why | BMAP behavior model + empathy questions | `references/behavior-model.md` |
| Auditing or redesigning a **single screen/prompt/dialog** | B.I.A.S. framework | `references/bias-framework.md` |
| Analyzing or improving a **multi-step flow** (onboarding, signup, upgrade) | Journey mapping (Peaks, Pits, Transitions) | `references/journeys.md` |
| Preparing a design review, justifying a decision, answering feedback | Communication tactics | `references/communicating.md` |
| Feature touches notifications, defaults, urgency, or attention | Ethics tests | `references/ethics.md` |

Read the relevant reference file before applying a framework — each holds the full principle lists, question templates, and a worked example (Airbnb 6P story, DoorDash B.I.A.S. redesign, Brave onboarding journey) showing how much change each step warrants. For a full feature review, the natural order is: behavior model (do we understand the user?) → journey (where does psych drop?) → B.I.A.S. (fix the weakest screens) → ethics (are we being humane?).

## How to run a review with this skill

1. **Ground in the actual experience** — read the relevant components/copy in the repo, or look at the screen (Storybook, screenshot, Figma) before theorizing. Critique what's really there, not an imagined version.
2. **State the desired behavior and the user's likely M·A·P** at that moment — one sentence each. If motivation is unknown, say so and suggest which GEQ/SEQ would answer it (don't invent user research).
3. **Walk the applicable framework step by step**, quoting the concrete UI element or copy string each finding refers to.
4. **Output findings as: observation → principle (named) → psych effect (+/−) → concrete suggested change.** Rank by expected psych impact, not by ease. A review that ends with three prioritized changes beats an exhaustive principle-by-principle essay.
5. **Close with the ethics pass** whenever a suggestion involves defaults, urgency, loss framing, or notifications.

## Core model in one paragraph

Behavior happens only when **Motivation, Ability, and a Prompt** converge (B = M·A·P). Never try to force a behavior — align with what users already want (motivation), make it as easy as possible (ability), then cue it at the right moment (prompt). On any given screen, the brain runs a fast System-1 loop: it **Blocks** most stimuli, **Interprets** what passes the filter, decides whether to **Act**, and **Stores** the emotional outcome — which biases the next loop. Across a whole journey, memory is dominated by the Peak, the Pit, and the End (peak-end rule), not the average.

## Quick audit checklist (single interaction)

Put yourself in the user's shoes and ask, in order:

1. **Block** — Does this pass my brain filters, or does it look high-effort, redundant, unrelated, or ad-like?
2. **Interpret** — What do I understand from this? Is the benefit clear and framed around *my* hopes, not the product's features?
3. **Act** — How easy is it to take action? Count the decisions on the page; remove options, use valid defaults, split steps.
4. **Store** — Was it satisfying? Clear feedback, reassurance, a sign the product cares about my outcome?

## Communicate checklist (design reviews)

To rally a team around a decision, bring three things: a **story** (rallies people around the user, not opinions), **business goals** (know how the work impacts the business; empathize with stakeholders like you would with users), and **vocabulary** (naming the psychological principle behind a decision dissolves taste-based objections). Before a product review, answer:

- What's the goal of this review, and what do I want feedback on? (create feedback guardrails — never show designs without saying what feedback you want)
- What problem does this solution solve — and is it a business problem?
- How does it currently affect users? (what's the story behind it?)
- Why is this solution better than the alternatives?

For answering feedback (lead with a yes → repeat and empathize → assure), handling difficult archetypes ("I don't like it", "why change anything", "let's change everything"), and the key-sentences vocabulary, read `references/communicating.md`.

## Upheal-specific notes

- "User" here is usually a **provider** (therapist); some flows target clients via the Client Portal. Provider psych is drained by clinical workload — respect their time and attention doubly.
- Journey analysis pairs well with PostHog funnels: the biggest Drop in a funnel is where to point the B.I.A.S. audit.
- Nudges (social proof, scarcity, curiosity) must clear the ethics tests in `references/ethics.md` — this is a healthcare product; reactance and distrust are costlier than a missed conversion.

Source: Lukas's Growth design notes — https://horaklukas.notion.site/Growth-design-1ea176e189858187b3e4c0d4ba79be61
