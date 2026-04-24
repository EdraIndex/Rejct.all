# Drop plan

## Purpose
Generate a full drop launch plan per Playbook 01.

## Input
- Drop name (or request one)
- Pieces in the drop (count, types)
- Target drop date
- Anything the drop refuses on top of the default rejections

## Prompt

```
Generate a Rejct.all drop plan following PLAYBOOK_LIBRARY.md Playbook 01 exactly. Follow CLAUDE.md tone rules for all copy.

Drop name: [name or "suggest 3"]
Pieces: [list]
Drop date: [date]
Specific refusal: [what this drop refuses beyond the defaults]

Produce:
1. Confirmed drop name.
2. One Hindi line for the drop (Devanagari).
3. One English line for the drop.
4. Product copy for each piece (name + ≤40-word description).
5. Waitlist-open statement (1–2 sentences, date included).
6. Drop-live time (a non-obvious time in IST).
7. The single 48-hour-after image caption (Hindi line only, or silence).
8. Sold-through archive label.
9. Anti-pattern checklist confirming what we will not do (from Playbook 01).
```

## Output expectations
- Every section filled.
- No marketing language.
- Anti-pattern checklist calls out hype sequences, BTS content, thank-you posts.
