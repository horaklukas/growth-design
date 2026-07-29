# growth-design

An agent skill for [Claude Code](https://claude.com/claude-code) that applies product-psychology frameworks from the [Growth.Design](https://growth.design) course when designing or reviewing user-facing experiences.

## What's inside

- `SKILL.md` — the entry point: core psych-level model, framework routing table, review workflow, and quick audit checklists.
- `references/behavior-model.md` — B = M·A·P behavior model, empathy questions (GEQs/SEQs), Psych framework, 6P stories.
- `references/bias-framework.md` — the B.I.A.S. loop (Block → Interpret → Act → Store) for auditing a single screen, with the DoorDash worked example.
- `references/journeys.md` — journey mapping (Peaks, Pits, Transitions) and the four improvement tactics, with the Brave onboarding worked example.
- `references/communicating.md` — presenting and justifying product decisions, answering feedback, handling difficult archetypes.
- `references/ethics.md` — regret test, manipulation matrix, Black Mirror test, humane-design principles.

## Install

Copy the repository content into a skill directory:

```
# project-scoped
.claude/skills/growth-design/

# or user-scoped
~/.claude/skills/growth-design/
```

The skill triggers on requests to design or critique UX flows, screens, onboarding, dialogs, notifications, or questions like "why aren't users doing X".
