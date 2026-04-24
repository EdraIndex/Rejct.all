---
name: tone-check
description: Review any draft copy against Rejct.all tone rules (direct, terse, non-aspirational, never ironic, bilingual by design). Use when the user pastes copy and asks for a review, or whenever generated copy needs a check before being finalized.
---

# tone-check

Review the draft copy provided and return a pass/fail verdict with a rewrite if needed.

## Steps

1. Read the draft.
2. Apply the tone rules from `CLAUDE.md`:
   - Direct, terse, non-aspirational, never ironic, emotionally controlled.
   - No hype, no slang, no explanation-heavy copy, no emoji, no exclamation points.
   - Bilingual only where Hindi strengthens what the English cannot say alone.
3. Return:
   - **Verdict:** `pass` or `fail` (one word).
   - **If fail:** a short list of specific violations.
   - **Rewrite:** a shorter, stricter version that passes. If the original already passes, say so and do not rewrite.
4. Never soften the rewrite to be "friendlier." Tone is the product.

## Output format

```
Verdict: [pass | fail]

Violations:
- [specific violation]
- [specific violation]

Rewrite:
[rewritten copy]
```

If the verdict is `pass`, omit the violations section and say `No rewrite needed.`
