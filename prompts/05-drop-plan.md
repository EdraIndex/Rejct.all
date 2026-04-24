# Drop plan

## Purpose
Generate a full drop plan using the Brand Bible 4-phase Instagram launch model and the drop-construction rules.

## Input
- Drop number (sequential, no 01.5)
- Volume label (00: Before, 01: After, etc.)
- Season (S/S or F/W + year)
- Styles in the drop (must be min 4, max 8, include ≥1 tonal, ≥1 back-hero, `R.` monogram present)
- Target drop window (per Bible roadmap)

## Prompt

```
Generate a drop plan for rejct.all. Follow PLAYBOOK_LIBRARY.md Playbook 01 and Brand Bible §08, §09, §10 exactly. Follow CLAUDE.md voice rules for all copy.

Drop: [Drop XX]
Volume: [Volume XX: Name]
Season: [season + year]
Styles (count + descriptions): [list]
Target window: [window]

Produce:

1. Drop name + volume + season tagline.

2. Style list with SKU assignment (RJ-XXX).
   Confirm: min 4 / max 8 styles, at least one tonal, at least one back-hero piece, R. monogram present.

3. Phase 1 — Before (2–3 weeks pre-drop) content plan.
   One rejection per day, both languages. R. monogram standalone posts.

4. Phase 2 — Reveal (1 week pre-drop) content plan.
   Detail close-ups. Which details per day.

5. Phase 3 — Drop day content plan.
   One editorial post per style, front and back. Bilingual caption template per post.

6. Phase 4 — After content plan.
   Reposts of real wearers. Single "no restock" reminder. Volume 01 teaser start.

7. Product copy block for each SKU (format from templates/product-copy.md).

8. Anti-pattern confirmation — explicitly state we will not do:
   - Countdowns
   - Hype ladder posts
   - BTS manufacturing content
   - Thank-you posts after sellout
   - Re-announcements

Hard constraints:
- Brand name lowercase throughout.
- No hype words.
- No GSM or fabric spec language in any customer-facing copy.
- Every caption has both Hindi and English.
- No hashtags in captions.
```

## Output expectations
- All 8 sections filled.
- Bilingual content in Phases 1, 2, 3.
- Anti-pattern checklist explicit.
- Product copy passes the voice test.
