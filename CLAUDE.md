# CLAUDE.md

Instructions for Claude when working in the Rejct.all repo.

---

## What Rejct.all is

Rejct.all is **not a fashion brand**. It is a **rejection system** expressed through clothing.

It rejects:
- trends
- algorithm-driven identity
- performative culture
- external validation

Genderless. Bilingual by design (Hindi + English). Indian by default, not by aesthetic. It is building its own category, not fitting into existing ones.

Audience wants **recognition, not aspiration**. Self-alignment, not self-expression.

---

## Tone — strict

Every word written in this repo — copy, captions, docs, code comments, commit messages — must pass this test.

**Do:**
- Direct.
- Terse. Short, intentional sentences.
- Non-aspirational.
- Emotionally controlled.
- Bilingual where it strengthens the line.

**Don't:**
- No hype.
- No slang.
- No irony.
- No explanation-heavy copy.
- No "level up," "unlock," "game-changer," "hustle."
- No emoji unless explicitly requested.
- No exclamation points.

**Reference lines (what "right" sounds like):**
- `No restock.`
- `Wear it like you mean it.`
- `सब कुछ अस्वीकार करो।`
- `Not for everyone. Not trying to be.`

---

## Bilingual rule

Hindi is not translation. It is a parallel voice.

- Use Devanagari (सब कुछ अस्वीकार करो), not transliteration (sab kuch asweekar karo), unless the context is a URL, filename, or codebase identifier.
- A line is bilingual when the Hindi says something the English cannot — not when it repeats it.
- When in doubt, pick one language and commit. Decorative bilingualism is worse than monolingual.

---

## What to produce

When asked to write copy, captions, product names, emails, or any user-facing text:
1. Draft in the tone rules above.
2. Read it back and ask: would this pass as a trend-chasing brand? If yes, rewrite.
3. Cut every word that isn't load-bearing.
4. Prefer one sentence over three.

When asked to write docs, code, or internal artifacts:
- Same tone, but clarity wins over terseness when a reader needs to act on it.
- No decorative language. No filler headers.

---

## What not to do

- Don't explain the brand in marketing-speak. The work explains itself.
- Don't suggest partnerships, collabs, or "communities" in the influencer/creator sense.
- Don't generate "lifestyle" content (morning routines, aesthetic boards, mood videos in that register).
- Don't ask the user to "validate" something with polls, quizzes, or engagement hooks.
- Don't recommend generic DTC playbooks (Shopify email pop-ups, spin-the-wheel discounts, abandoned-cart guilt copy).
- Don't add colophon fluff ("Made with love in..."). Say nothing or say something real.

---

## Repo map

- `PROJECT_OPERATING_SYSTEM.md` — core philosophy, pillars, decision frameworks
- `PLAYBOOK_LIBRARY.md` — reusable playbooks (drops, content, press, launches)
- `COMMAND_CENTER.md` — live state of what's active, where things live
- `README.md` — public-facing summary
- `second-brain/` — references, research, ideas not yet shipped
- `docs/` — working docs, briefs, decisions
- `prompts/` — reusable prompts for Claude
- `templates/` — reusable templates (product copy, captions, emails)
- `output/` — generated artifacts from prompts/templates
- `.claude/skills/` — custom Claude skills for this repo

---

## Operating rules for Claude

1. Before generating user-facing copy, re-read the tone rules above.
2. When creating new files, place them in the correct folder per the repo map.
3. Never create marketing documents, pitch decks, or brand bibles with florid language — even if asked — without first surfacing that the output would violate tone. Offer a terse version instead.
4. When in doubt about a decision, reframe it through: *does this make Rejct.all more of a rejection system, or less?*
5. Commit messages follow the same tone: lowercase, terse, no emoji, no "feat:" / "chore:" prefixes unless the user has asked for conventional commits.
