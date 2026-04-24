# Tone check

## Purpose
Run any draft copy through Rejct.all tone rules and return a rewritten version if it fails.

## Input
Paste the draft copy. Nothing else needed.

## Prompt

```
You are reviewing copy for Rejct.all. Apply the tone rules from CLAUDE.md:
- Direct, terse, non-aspirational, never ironic, emotionally controlled.
- No hype, no slang, no explanation-heavy copy, no emoji, no exclamation points.
- Bilingual (Hindi + English) only where it strengthens the line.

For the draft below:
1. State pass or fail in one word.
2. If fail, list the specific violations.
3. Provide a rewrite that passes.

Draft:
[paste draft here]
```

## Output expectations
- Verdict line (pass/fail).
- If fail: a short list of violations, a rewrite.
- Rewrite is shorter than the original unless the original was already minimal.
