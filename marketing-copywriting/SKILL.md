---
name: marketing-copywriting
description: Recommend and apply named rhetorical and persuasion techniques to create, improve, critique, or brainstorm marketing copy.
version: 1.1.0
author: dcaste
tags: [copywriting, marketing, advertising, headlines, persuasion]
---

# Marketing Copywriting

Use this skill to turn a copy brief into deliberate, explainable marketing copy. It recommends techniques before writing so users can choose a direction rather than receive generic variants.

The technique library is `references/copywriting-techniques.md`.

## When to use

Use this skill for new copy, submitted-copy critiques or rewrites, brainstorming, and requests to choose a copywriting technique. It covers headlines, taglines, slogans, ads, CTAs, email subject lines, social captions, and landing-page copy.

## Workflow

1. **Read the copy brief.** A goal or an existing line alone is enough. Product, audience, channel, tone, output type, and funnel stage are useful but optional.
   - State any assumption that affects the response, then ask one short question that would improve the next iteration.
   - Do not block on ordinary missing context. Pause before writing only when missing information would materially affect accuracy or safety—for example, a regulated claim, an unknown product, or an unverified comparative claim.
   - If the user says `Direct mode` or `Just the copy`, honor the requested technique, format, count, and tone with minimal explanation.
2. **Diagnose submitted copy.** When existing copy is supplied, briefly say what it communicates, what limits it for the stated goal, and whether it should be refined or replaced.
3. **Select techniques deliberately.** Read the Quick Reference Table and Usage Guide in `references/copywriting-techniques.md`, then shortlist 3–6 suitable techniques. Read the entries only for the techniques you select.
   - Recommend each technique with a short reason and its best use.
   - If the user names a technique, recommend it concisely and use its entry directly.
   - Avoid Pun, Self-Deprecation, and Chuck Norris for medical, legal, or financial businesses. Flag conditions for high-risk techniques (Anomaly, Bash Competitors, Shock Headlines) instead of silently omitting them.
4. **Write the requested number of copy options.** The requested count is the total number of options, not the number per technique. Distribute options across the best-fit techniques. Default to three options when no count is requested.
5. **Keep each option focused.** Use no more than one or two techniques in one piece of copy. For long-form assets, use Group D/E for structure and reserve Group A/B for headlines.

## Response format

Use this order, omitting sections that do not apply:

```md
**Assumptions**
[Only assumptions that affect the response, plus one useful clarifying question.]

**Copy diagnosis**
[Only when copy was supplied: what it communicates, what limits it, and refine vs. replace.]

**Technique recommendations**
- **[Technique]** — [why it fits]. Best for: [case].
- **[Technique]** — [why it fits]. Best for: [case].

**Copy options**
1. "[Copy]" ([Technique])
2. "[Copy]" ([Technique])
3. "[Copy]" ([Technique])

**Next step**
[One brief suggestion for testing or refining the direction.]
```

In direct mode, retain a one-line recommendation and the labeled options; omit diagnosis, assumptions, and next-step advice unless necessary or requested.

## Examples

**Goal-only brief:** “Get more demo bookings for a payroll app.”

Recommend conversion techniques, state any assumptions about audience or channel, then produce three labeled options.

**Submitted copy:** “We make accounting easy.”

Diagnose the vague promise, recommend a more specific technique, then provide rewrites.

**Named technique:** “Direct mode: give me three Antithesis headlines for a gym.”

Briefly confirm Antithesis as the recommendation, then provide exactly three labeled headlines.
