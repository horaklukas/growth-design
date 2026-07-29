# B.I.A.S. framework — audit and redesign a single screen

The brain runs a fast System-1 loop on every screen: **Block → Interpret → Act → Store**. Most decisions are System 1 (automatic, instinct + prior learning), not System 2 (slow, deliberate). Design for the fast path. Work through the four steps in order — each redesign iteration builds on the previous one.

## High-level pass

Put yourself in the user's shoes:

1. **Block**: Does this pass my brain filters?
2. **Interpret**: What do I understand from this?
3. **Act**: How can I take action?
4. **Store**: Was the overall interaction satisfying — clear and reassuring?

## Block — help users see what's important

The brain automatically filters out anything that is:
- 🧮 **High-effort** — we take the path of least resistance; too many choices trigger action paralysis (Hick's law)
- 🌵 **Unrelated** — anything not related to the current goal is filtered (selective attention)
- 👯 **Redundant** — patterns seen too often get filtered (banner blindness); also anything that looks like an ad or sits in a typical ad position

Attention is captured by things that are:
- 🐟 **In short-term memory** (priming)
- 💚 **Confirming beliefs** (confirmation bias)
- 🎲 **Unexpected** — pattern breaks, humor, personalization

Audit questions: Are things redundant or unrelated? Does it look like a high-effort commitment? Does it look like an ad? Is there any unexpectedness? Is the prompt's timing aligned with real behavior? Frame value around the user's hopes and pains to earn attention.

## Interpret — help users establish a good frame of reference

Seven reframing principles:
- 👨‍👩‍👧‍👦 **Familiarity** — reuse existing patterns to lower processing cost
- 🚛 **Cognitive load** — cut noise around the critical information (visuals, text-heaviness)
- 🍇 **Benefits** — lead with what's in it for the user, aligned to their hopes; features don't persuade
- ⚓️ **Anchoring** — give comparisons so people have a frame of reference
- 🗑 **Loss aversion** — show what's at stake on non-action (tie it to benefits, don't just threaten)
- 👀 **Discoverability** — make key actions stand out
- 🧗 **Labor illusion** — show work happening behind the scenes; turn waiting periods into value

Redundancy (Block) vs familiarity (Interpret) are the same concept in different situations: don't use redundant elements when trying to *capture attention*; use familiarity when trying to *simplify interpretation and action*. Framing is powerful — a few words can move behavior; it's also where influence tips into manipulation (see `ethics.md`).

## Act — help users achieve their goals

Reduce friction:
- 🗑 **Remove options** — more choices, slower decisions (Hick's law)
- 🚦 **Valid defaults** — design so user input isn't required
- ✂️ **Split steps** — three small steps beat one big one (cognitive load)
- 🌱 **Reveal gradually** — progressive disclosure; count the decisions per page

Nudge carefully (reserve for key actions — overuse breeds banner blindness and reactance):
- 👥 **Social proof** — showing what others did reassures
- 💭 **Curiosity gap** — an information gap people feel compelled to fill
- 🦄 **Scarcity** — limited things feel more desirable

## Store — make every interaction count

Users keep a running tab of every interaction; stored psych biases the next Block → Interpret → Act loop. Repeated positive loops become habits. In order of impact:

1. 👀 **Clear feedback** — every interaction shows what just happened
2. 👊 **Reassurance** — confirm they did the right thing; "in good hands"
3. 💙 **Caring** — visible interest in the user's outcome, not just the conversion
4. 🍭 **Delighters** — going above and beyond; simple humanity often delights more than fancy animation

Audit questions: Are basic expectations covered? Is feedback clear? Do users feel reassured after acting? Any small interactions worth delighting on? Are you building a positive relationship (helpful guide, not the pushy salesman)? Ending on a strong note also offsets earlier rough moments (peak-end rule).

## Worked example — DoorDash DashPass prompt

The course redesigns one real upsell prompt through all four steps; use it as the template for how much to change at each step:

1. **Block**: the original prompt was text-heavy with an alarming color, so the brain filtered it out. Fix: shorter title (easier scanning), smaller sentences (easier reading), calmer color (less ad-like).
2. **Interpret**: reframe the copy around the single biggest user benefit — *saving money* — instead of describing the feature. A few words of framing can move behavior more than any visual change.
3. **Act**: only one small addition — social proof ("X people are already saving with DashPass") to reassure hesitant users. Deliberately minimal: pushy nudges create reactance.
4. **Store**: design what happens *after* the tap — a confirmation combining reassurance ("you made a good decision") and caring (free monthly savings reports so the user always knows they're getting value).

Pattern to copy: each step makes a small, targeted change; the compounding of four small changes is the redesign. There are hundreds of valid answers — the framework's value is making you consider each stage explicitly.
