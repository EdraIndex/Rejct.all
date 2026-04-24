# Draft product copy

## Purpose
Generate product copy for a new piece, aligned to Brand Bible §06 and §09.

## Input
- SKU number (next in sequence)
- Piece type (e.g., tee, sleeveless, shirt)
- Colourway (default palette: Wine Red, Olive, Tonal)
- Graphics / placement (chest, back, collar, hem)
- Fabric in feeling-language (Bible §06 examples)

## Prompt

```
Write product copy for rejct.all. Follow CLAUDE.md voice rules and Brand Bible §06 and §09.

SKU: [RJ-XXX]
Piece: [type]
Colourway: [colourway]
Graphics: [what is on the garment and where]
Fabric feel: [feeling-language, no specs]

Format:
[SKU] — [Name · Colourway]
₹[price]
[1–2 sentence description — what is on the garment. No story arc. No hype. No explanation of brand philosophy.]
[Material line — feeling, not specs.]

Hard constraints:
- Brand name lowercase (`rejct.all`).
- No fabric specifications (GSM, blend percentages, "premium", "luxury", "heavyweight").
- No hype words (`drop` as hype, `collab`, `cop`, `fire`, `goes hard`).
- No exclamation points. No emoji.
- Description mentions where the design sits (chest / back / collar / hem).
```

## Output expectations
- Product block in the exact format above.
- Copy a trend-chasing brand could not have written.
- Material line in Bible-style feeling language.
