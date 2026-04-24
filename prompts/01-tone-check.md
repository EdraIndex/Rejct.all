# Tone check

## Purpose
Run any draft copy through `rejct.all` tone rules and return a rewritten version if it fails.

## Input
Paste the draft copy. Nothing else needed.

## Prompt

```
You are reviewing copy for rejct.all. Apply CLAUDE.md tone rules and Brand Bible §07:
- Direct, terse, bilingual by default, never ironic, never aspirational.
- Brand name always lowercase (`rejct.all`). Never `Rejct.all` or `REJCT.ALL`.
- No hype words: `drop` (as hype), `collab`, `cop`, `fire`, `goes hard`.
- No emoji, no exclamation points, no slang.
- For captions specifically: Hindi AND English together, never one alone.
- No fabric specifications (GSM, blend percentages) in customer-facing copy.

For the draft below:
1. State pass or fail in one word.
2. If fail, list the specific violations (cite the rule each violates).
3. Provide a rewrite that passes.

Draft:
[paste draft here]
```

## Output expectations
- Verdict line (pass/fail).
- If fail: a short list of violations, a rewrite.
- Rewrite is shorter than the original unless the original was already minimal.
