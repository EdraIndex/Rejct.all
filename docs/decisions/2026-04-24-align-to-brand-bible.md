# Align the OS to the Brand Bible

Date: 2026-04-24
Status: accepted

## Context

The Brand Bible v2.0 (S/S 2026) is the canonical source of truth for `rejct.all`. The OS files generated earlier this day were drafted from a verbal brief before the Bible was available and contained contradictions against it — the most consequential being brand-name capitalization, pillar structure, caption bilingual rule, and default-refuse press policy.

## Decision

- `Brand Bible.md` becomes the single source of truth.
- `PROJECT_OPERATING_SYSTEM.md`, `PLAYBOOK_LIBRARY.md`, `COMMAND_CENTER.md`, `CLAUDE.md` were rewritten to translate the Bible into operating rules without contradicting it.
- `BRAND_SYSTEM_MAP.md` was added to map each of the Six Rejections to concrete rules across Content / Product / Drops / Customer Experience.
- Templates and prompts with direct contradictions were rewritten (`templates/caption.md`, `templates/drop-announcement.md`, `templates/press-reply.md`, `templates/customer-reply.md`, `templates/product-copy.md`, `templates/email.md`, `prompts/02`, `prompts/04`, `prompts/05`).
- `README.md` updated to reflect lowercase brand name and the Six Rejections as pillars.

## Why

Tested against OS pillars (now the Six Rejections):
- Reject the label — the earlier pillars were an invention that competed with the Bible's own structure. Replacing them restores a single taxonomy.
- Reject performing — the prior press policy (default refuse) over-performed "no" as a brand posture; the Bible is more specific (refuse paid placement, open to editorial).
- Reject everything that isn't you — silent contradictions between repo and Bible would compound into drift. This aligns them before they harden.

## Consequences

- The Bible is versioned and leads. This repo updates when the Bible updates.
- Older files (earlier templates, prompts, decision 2026-04-24-adopt-project-os.md) remain as history; contradictions in them have been corrected in place where critical, or noted for a second pass.
- Future changes to the OS require a decision record in `docs/decisions/` and must not silently contradict the Bible.
