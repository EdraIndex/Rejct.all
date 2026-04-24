# Draft Hindi line

## Purpose
Generate a standalone Hindi line in Devanagari for a site, drop, or piece.

## Input
- Context (home page, drop name, product tag, email signoff, etc.)
- The feeling the line should carry (refusal, recognition, stillness, stance)
- English line if any (the Hindi should not translate it)

## Prompt

```
Write one Hindi line in Devanagari for rejct.all. Follow CLAUDE.md voice rules and Brand Bible §07 (bilingual, never translated).

Context: [context]
Feeling: [feeling]
Paired English (do not translate this): [English line or "none"]

Constraints:
- Devanagari only. No Roman transliteration.
- Maximum 8 words.
- Must stand alone — not a translation of the English.
- No irony, no hype, no devotional register, no film-dialogue register.
- Register to match Bible reference lines: `सब कुछ अस्वीकार करो।`, `पहनो जैसे मतलब हो।`, `सूती। भारी। ईमानदार।`.

Produce three options. For each, add a one-line note on the nuance (what it says that plain English cannot).
```

## Output expectations
- Three options, each under 8 words, in Devanagari.
- Each has a one-line nuance note.
- None is a translation of the English input.
