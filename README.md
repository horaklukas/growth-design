# growth-design

Turn your AI agent into a growth designer — an [agent skill](https://skills.sh) that reviews and improves any user-facing experience using the product-psychology frameworks taught by [Growth.Design](https://growth.design).

Most UX feedback is subjective ("this feels clunky"). This skill makes it structural: every finding names the psychological principle at play, states its effect on the user, and proposes a concrete change — ranked by impact, not by ease.

> The anchor metric: every user has a **Psych level** (mental energy). Each interaction adds psych (motivation, clarity, delight) or drains it (friction, confusion, distrust). **Psych = Motivation − Friction.** When it hits zero, the user drops out.

---

## 🛠 Included frameworks

- **B = M·A·P behavior model** — behavior happens only when Motivation, Ability, and a Prompt converge; includes the empathy-question templates (GEQs/SEQs) to find the missing lever.
- **Psych framework** — annotate a screen with the user's psych gains and drains in scan order; the biggest drops are your redesign targets.
- **B.I.A.S. loop** — Block → Interpret → Act → Store: how the brain's System 1 processes a single screen, with principles and audit questions for each step.
- **Journey mapping** — boil a flow down to its Peak, Pit, Jumps, Drops, and Transitions; four proven tactics to improve it (peak-end rule).
- **Communication tactics** — justify decisions with stories, business goals, and named principles; answer difficult feedback gracefully.
- **Ethics tests** — regret test, manipulation matrix, Black Mirror test; keeps nudges on the influence side of the line.

Each framework lives in its own file under [`references/`](references/) with the full principle lists and a worked example (Airbnb 6P story, DoorDash B.I.A.S. redesign, Brave onboarding journey).

---

## 🚀 Install

```sh
npx skills add horaklukas/growth-design
```

Works with Claude Code, Cursor, GitHub Copilot, and other agents supported by the [skills CLI](https://skills.sh).

Or manually — copy the repository content into a skill directory:

```
.claude/skills/growth-design/      # project-scoped
~/.claude/skills/growth-design/    # user-scoped
```

---

## 💬 Usage

Example prompts that trigger the skill:

- *"Review the password reset flow through a growth-design lens"*
- *"Why aren't users finishing onboarding? The funnel drops 40% at step 3"*
- *"Audit this upgrade dialog before we ship it"*
- *"Help me prepare the design review for the new scheduling screen"*

### Example output

Findings follow **observation → principle → psych effect → concrete change**:

| # | Observation | Principle | Psych | Suggested change |
|---|---|---|---|---|
| 1 | Validation error says only "Password is invalid"; submit stays disabled with no explanation | Clear feedback | − | Live checklist that ticks each password rule as it's satisfied |
| 2 | SMS code requirement appears with no warning after the email step | Untimely pattern break | − − | Mention the code on the email-sent card, *before* the pit occurs |
| 3 | Success screen sends the user to sign-in with an empty email field | Peak-end rule | − | Carry the email over — end the draining flow on a high note |

A review ends with the top 3 changes ranked by psych impact and an ethics pass on any suggestion involving defaults, urgency, or loss framing.

---

## 📂 Repository structure

```
growth-design/
├── SKILL.md                       # Entry point: routing table, review workflow, audit checklists
└── references/
    ├── behavior-model.md          # B = M·A·P, empathy questions, Psych framework, 6P stories
    ├── bias-framework.md          # Block → Interpret → Act → Store + DoorDash example
    ├── journeys.md                # Peaks, Pits, Transitions + Brave onboarding example
    ├── communicating.md           # Design reviews, feedback answers, difficult archetypes
    └── ethics.md                  # Regret test, manipulation matrix, Black Mirror test
```

---

## 🤝 Contributing

1. Fork the repository
2. Improve a reference file or the SKILL.md workflow
3. Open a pull request describing what the change improves and why

---

## ⚖️ License & attribution

The framework concepts are taught by [Growth.Design](https://growth.design) — this repository is an independent distillation for agent use and is not affiliated with or endorsed by Growth.Design. If this material resonates, take [their course](https://growth.design/psychology); it's excellent.
