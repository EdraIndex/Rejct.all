---
name: caption-engine
description: Generate up to three Instagram captions for rejct.all from an idea or context. Each caption maximum 8 words. No explanation, no CTA, no hashtags, no emoji. If no caption fits, says so. Use when a caption is needed for a specific post, image, or drop phase.
---

# caption-engine

**This skill does not help. It produces.** The output is captions or a refusal. Nothing else — no framing sentence, no "here are a few options," no commentary on which one is strongest.

---

## Rules

1. **Maximum 3 captions.** Fewer if fewer survive. Never more.
2. **Maximum 8 words per caption.** Hindi + English combined. Count each Devanagari word as one.
3. **Bilingual by default for Instagram captions.** Per Bible §10. Hindi and English together, never one alone.
4. **Bilingual is optional for other surfaces** (email subject, product tag, site header). Use bilingual only when the Hindi carries meaning the English cannot. Never decorative.
5. **No CTA.** Never `Shop now`, `Link in bio`, `Tap to buy`, `DM us`, `Drop [X] available`.
6. **No hashtags.** Not in the caption. Not in the first comment instructions.
7. **No @mentions.** Unless it is a direct credit, which is rare.
8. **No emoji. No exclamation points.**
9. **No explanation.** No "here are three," no "option 1 is stronger."

---

## Output — captions produced

```
1. [caption]
2. [caption]
3. [caption]
```

Only the list. Nothing before, nothing after.

If only one or two survive:
```
1. [caption]
2. [caption]
```

---

## Output — nothing fits

When the brief cannot produce a caption that passes:

```
No caption fits.

Reason: [one line — which rule the brief forces a violation of]
```

Do not produce a placeholder. Do not produce a softer version. A bad caption is worse than no caption.

---

## Reference register

Captions should sit at the temperature of these:

- `सब कुछ अस्वीकार करो। Reject everything.`
- `Cotton. Heavy. Honest. सूती। भारी। ईमानदार।`
- `नज़र को नकारो। No gaze.`
- `पहनो जैसे मतलब हो। Wear it like you mean it.`
- `ट्रेंड को नकारो। Reject the trend.`

If the draft reads warmer, cleverer, or more helpful than these — cut it or replace it.

---

## Internal check before producing

Before the list is returned, every caption passes through:

1. Does it feel like refusal?
2. Is it trying to impress?
3. Is it explaining too much?
4. Could a trend brand have posted this?

Any fail → the caption is cut from the list before the user sees it.
