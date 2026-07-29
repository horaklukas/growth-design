# Customer journeys — mapping and improving multi-step flows

Use for onboarding, signup, upgrade, or any multi-step experience. Memory doesn't average an experience — it heavily weighs the **Peak**, the **Pit**, and the **End** (peak-end rule).

## Mapping a journey

Don't build exhaustive journey maps — they're hard to build, share, and act on. Boil the experience down to its **top 5–6 moments** (Miller's law: this is what a brain can hold):

| Element | Description |
|---|---|
| 🏔 Peak | Highest absolute psych level in the experience |
| 🕳 Pit | Lowest absolute psych level |
| 🌈 Jump | Biggest relative psych increase |
| 💧 Drop | Biggest relative psych decrease |
| 🏁 Transition | Moment marking the start or end of a milestone |

- Vertical axis = psych level; use faces/emojis per moment, not abstract dots — emotion communicates.
- Map what's **really happening** (data, funnels, support tickets), not the ideal happy path.
- Too many steps? The slice is too broad — break into sub-journeys. Transitions are real milestones ("left the house", "arrived at airport"), not micro-steps.

## Improving a journey

Four proven tactics, in the order they usually pay off:

1. **Mark the 🏁 Transition** — celebrate key milestones; clarity of the transition should be proportional to the milestone's importance.
2. **Elevate the ⛰ Peak** — lean into the customer's motivations (hopes, fears).
3. **Fill the biggest 🕳 Pit** — look slightly *before* the pit for the root cause; revisit BMAP and B.I.A.S.
4. **Reorder steps** — could moving a high-psych moment earlier make the journey simpler and more memorable? Users need enough psych left to finish on a high note.

Don't play whack-a-mole with every small pothole — Pareto: the key moments dominate memory.

Supporting principles:
- 🧠 **Hyperbolic discounting** — people prefer a small immediate reward over a larger future one; deliver a preview of value now instead of making users wait.
- ⏳ **Waiting periods** — shorten them, or use them to educate, reassure, or delight (labor illusion).
- 📊 **ROI of delight** — moving good customers (NPS 5–8) to delighted (9–10) returns ~9× more revenue than moving unhappy customers to neutral (Forrester, 2017).
- 🤡 **"In real life" test** — which part of the digital flow would feel most awkward as a face-to-face interaction? Fix that.

## Improvement brainstorm checklist

- What's the root cause of the biggest Jump? (what context/motivation made it work?)
- What's the root cause of the biggest Drop? (look slightly before it)
- How could the Pit be filled — is it a slow slope or a sharp drop?
- How could the Peak be elevated?
- Are Transitions marked proportionally to their importance?
- Could steps be reordered around Peaks/Pits/Transitions?
- Can waiting periods be shortened or turned into value?

Then: write the top 3 ideas, rank by impact-vs-effort focused on Peak/Pit/Transition, and explore one (revamped 6P story, wireframe, or mockup).

## Worked example — Brave browser onboarding

The course maps Brave's onboarding and improves it with exactly the four tactics — a template for choosing *which* screens deserve redesign:

- **Mark the Transition**: the moment a visitor goes from passively browsing the website to deciding to download the app is a big commitment — the redesign celebrates and reinforces that milestone instead of treating it as just another click.
- **Fill the Pit**: the lowest-psych moment was an *untimely prompt* — asking the user to make Brave their default browser before they'd even tried it — compounded by the fear of manually re-importing hundreds of bookmarks. And the actual import step was so quick that a drained user almost missed it. The fix addresses the fear at the moment it occurs, not later.
- **Elevate the Peak by reordering**: the most impressive screen (the dashboard showing ads blocked and time saved) came last. Moving a preview of it to the *first* onboarding step shows key benefits immediately, and primes users to push through the boring steps (import, settings).

Note what was *not* done: no attempt to polish every screen. Only the moments that dominate memory (Peak, Pit, Transition) got redesign effort.
