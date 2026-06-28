---
name: marketing-copywriting
description: Generate marketing copy (headlines, taglines, CTAs, social captions, email subject lines, landing pages) using 63 named rhetorical and persuasion techniques.
version: 1.0.0
author: dcaste
tags: [copywriting, marketing, advertising, headlines, persuasion]
---

# Marketing Copywriting

## Overview

A skill for generating marketing copy by deliberately applying named rhetorical and persuasion techniques, instead of writing generic copy from scratch. The full technique library lives in `references/copywriting-techniques.md`.

Generic copy ("Great food, great prices!") blends into the noise. Copy built on a named technique has a specific cognitive mechanism behind it — sound patterns, contrast, loss aversion, pattern-breaking — that makes it more memorable and persuasive.

## When to Use

Trigger this skill when the user asks to:

- Write, punch up, brainstorm, or get ideas for any marketing or advertising copy
- Generate headlines, taglines, slogans, ad hooks, CTAs, social captions, email subject lines, or landing page copy
- Improve or critique existing copy
- Apply a specific tone (witty, bold, no-nonsense, playful) to a piece of copy
- Understand why existing copy isn't working or compare technique options

## Instructions

1. **Gather the brief.** Before writing, make sure you know (ask only what's missing and only if it would clearly change the output):
   - The product/business and industry.
   - The specific output needed: headline, tagline, full ad, CTA, email subject line, social caption, landing page copy, etc.
   - The channel (print, social, email, OOH, landing page) — this affects which techniques are usable (Typographic Simile and Text Highlights only work visually).
   - The brand tone, if discoverable from context (playful, premium, no-nonsense, irreverent, corporate). If unknown and it would change technique selection, ask once.
   - The funnel stage / goal: attention (awareness), decision (conversion), or voice (retention/branding).

2. **Select techniques deliberately.** Open `references/copywriting-techniques.md` and use the Quick Reference Table (one-line rule per technique) and Usage Guide (funnel stage / channel / risk) at the top of the file to shortlist 3–6 techniques that fit the brief. Avoid Pun, Self-Deprecation, or Chuck Norris for medical/legal/financial businesses; flag risk before using Shock Headlines or Bash Competitors.

3. **Write 2–3 variants per chosen technique**, not one. Range from safe to bold so the user has real choices, not near-duplicates.

4. **Apply combination rules:** max 1–2 techniques per single piece of copy; don't stack three rhetorical devices into one line.

5. **Flag risk, don't silently skip it.** If a technique is tagged "high risk" in the Usage Guide (Anomaly, Bash Competitors, Shock Headlines), still offer it if it's a genuine fit — but note the condition to verify (e.g., "this Anomaly claim only works if you can actually prove it's the only X in the area").

### Reading the reference file

Read in two passes, not all at once:

1. **Selection pass:** read the Quick Reference Table and Usage Guide (top of file) to shortlist techniques.
2. **Writing pass:** read only the chosen technique's entry for its construction rule and examples.

The library is organized in five groups — use the Table of Contents to jump:
- **A. Sound & Rhythm** — best for short headlines and naming.
- **B. Meaning & Contrast** — best for clever, idea-driven headlines.
- **C. Tone & Brand Personality** — best for brand voice and social content.
- **D. Persuasion Structures** — best for full ads, landing pages, and email.
- **E. Positioning, Pain & Competition** — best for conversion-focused copy.

## Output Format

Always label every line with its technique in parentheses — without the label the user has no way to learn or ask for "more like #3."

Default structure:

```
**[Technique name]**
1. [variant] (Technique name)
2. [variant] (Technique name)
3. [variant] (Technique name)

**[Technique name]**
1. [variant] (Technique name)
...
```

For a single requested line, label inline: `"Small shop, big results." (Antithesis)`.

## Examples

**Input:** "Write 3 headline options for a barbershop targeting busy professionals. Tone: no-nonsense."

**Output:**

**Asyndeton**
1. "In. Cut. Out." (Asyndeton)
2. "Book. Sit. Done." (Asyndeton)
3. "No wait. No fuss. No problem." (Asyndeton)

**Antithesis**
1. "Less time in the chair, more time ahead." (Antithesis)
2. "Your schedule is tight. Your cut shouldn't be." (Antithesis)
3. "Fast chair. Sharp look." (Antithesis)

**Time to Value**
1. "Fresh cut in 30 minutes. Guaranteed." (Time to Value)
2. "Walk in at 7. Back at your desk by 8." (Time to Value)
3. "Done before your first meeting." (Time to Value)

---

**Input:** "Improve this line for my auto shop: 'We fix cars fast and well.'"

**Output:**

The existing line attempts Parallelism but breaks the structure ("fast" and "well" aren't parallel). Stronger options:

**Parallelism**
1. "Fast repairs. Fair prices. First time, every time." (Parallelism)
2. "We fix it right. We fix it fast." (Parallelism)
3. "In by 8. Fixed by noon. Out by lunch." (Parallelism)

**Asyndeton**
1. "Diagnose. Fix. Done." (Asyndeton)
2. "Drop it off. Pick it up. Problem solved." (Asyndeton)

## Notes

- **User names a technique directly** ("give me a Chuck Norris line for my gym"): skip selection, go straight to that technique's entry in the reference file and write variants.
- **User wants to improve existing copy**: identify which technique the existing line is weakly attempting, then either sharpen it within that technique's rules or replace it with a better-fitting one.
- **Sensitive industries** (medical, legal, financial advice, safety-related): default to lower-risk techniques (Groups A, B, D); avoid Group C/E techniques that rely on irony, self-deprecation, or confrontation unless the user explicitly asks.
- **Long-form assets** (landing page, full email): use Group D/E techniques for structure; reserve Group A/B for the headline only — don't pepper rhetorical wordplay through body copy.
