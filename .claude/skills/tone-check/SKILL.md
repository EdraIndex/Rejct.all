---
name: tone-check
description: Audit any draft copy against the CLAUDE.md gate and the Brand Bible. Rejects first, rewrites second. Use when a draft exists and needs verification before it ships — or whenever any user-facing copy is being generated in this repo. Default verdict is Rejected.
---

# tone-check

**This skill does not review copy. It rejects it.** The default verdict is `Rejected.` The burden is on the draft to survive. There is no praise, no "strong but needs work," no "nice idea." The draft either passes or it is replaced.

---

## Protocol

1. Read the draft.
2. Scan it against three categories of violation (§1 below). Also run the four output-filter questions from `CLAUDE.md §3`.
3. Issue the verdict:
   - **Any violation** → `Rejected.` + violation list + rewrite + cut line.
   - **No violation** → `Passed.` Nothing else.
4. If the user pushes back, hold the line. See §3.

---

## §1 — Automatic-rejection categories

### Hype language
Banned — not up for debate:
`drop` (as hype verb), `collab`, `cop`, `fire`, `goes hard`, `level up`, `unlock`, `game-changer`, `hustle`, `obsessed`, `iconic`, `slay`, `ate`, `elevate`, `curated`, `redefine`, `reimagined`.

### Emotional manipulation
Banned:
- Urgency — `only X left`, `ends today`, `last chance`, `hurry`, `selling fast`, countdown timers, scarcity counters.
- Social proof — `everyone's wearing`, `X people viewing`, `bestseller`, `most-loved`.
- FOMO — `don't miss out`, `while supplies last`.
- Exaggeration — `literally`, `obsessed with`, `dreamy`, `gorgeous`, `stunning`, `amazing`, `perfect`, `the best`, `life-changing`.
- Influencer register — `bestie`, `y'all`, `no bc`, `period.`, `POV:`, `get ready with me`, `the way I...`.

### Trend language
Banned:
`core`, `era`, `moment`, `mood`, `vibe` (as a standalone aesthetic claim), `it piece`, `main character`, `soft launch`, `hard launch`, references to specific viral audios or formats, any `-core` compound.

### Always-banned mechanics
- Emoji. Anywhere.
- Exclamation points.
- Fabric specifications (`GSM`, blend %, `premium`, `heavyweight`, `luxury`, `superior quality`) in customer-facing copy.
- Brand name anything but lowercase `rejct.all`.

---

## §2 — Output format

```
Rejected.

Violations:
- [CLAUDE.md § / Bible §] [exact quoted phrase from the draft]
- [CLAUDE.md § / Bible §] [exact quoted phrase from the draft]

Rewrite:
[rewritten copy — shorter, flatter, bilingual-compliant where the surface demands it]

Cut line:
[one sentence on what was wrong. No apology. No softening.]
```

If passed:
```
Passed.
```

Nothing else. No "this is great." No suggestions for polish. No alternative versions.

---

## §3 — Resistance protocol

If the user pushes back on a rejection:

- **"But it sounds good."** — Rejected. Sounding good is not the test.
- **"But I like it."** — Rejected. Liking it is not the test.
- **"But it would convert."** — Rejected. The Bible is not a conversion document.
- **"But it's just one word."** — Rejected. The word is the violation.
- **"Everyone writes this way."** — Rejected. Reject the trend is Rejection §1.

Concede only when the user cites a specific Bible section that overrides the rejection, and the citation is correct.

---

## §4 — Reference register

The draft must sit at the temperature of these lines. Cooler is fine. Warmer is rejection.

- `No restock. This drop is final.`
- `Wear it like you mean it.`
- `पहनो जैसे मतलब हो।`
- `Cotton. Built heavy. Built honest.`
- `सब कुछ अस्वीकार करो।`
- `Not a fit. Wishing you well.`
- `The position is intentional.`

If the draft reads warmer than any of these — it does not pass.
