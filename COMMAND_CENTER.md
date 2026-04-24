# Command Center

The live state of Rejct.all. What's active, what's next, where things are.
This is the first file to open and the last file to update.

---

## Status

**Phase:** Foundation. Position documented. No product live yet.

**Last updated:** 2026-04-24

---

## Active

_Nothing in production. OS is being built._

---

## Next

- [ ] First product brief — what piece carries the position best on entry.
- [ ] Visual system — typography, photography rules, website scaffold.
- [ ] Manufacturing partners shortlist.
- [ ] Domain + handles secured and locked.
- [ ] First Hindi line for the brand mark.

Order of the above is not fixed. Sequencing is a decision to make deliberately.

---

## Where things live

| What                                      | Where                                   |
| ----------------------------------------- | --------------------------------------- |
| Brand position, pillars, decision framework | `PROJECT_OPERATING_SYSTEM.md`         |
| Repeatable procedures (drops, content, etc.) | `PLAYBOOK_LIBRARY.md`                |
| Instructions for Claude                   | `CLAUDE.md`                             |
| Public-facing summary                     | `README.md`                             |
| Decisions log (proposals, reversals)      | `docs/decisions/`                       |
| Working briefs (product, visual, copy)    | `docs/briefs/`                          |
| References, research, saved inputs        | `second-brain/`                         |
| Reusable prompts for Claude               | `prompts/`                              |
| Reusable templates                        | `templates/`                            |
| Generated output from prompts/templates   | `output/`                               |
| Custom Claude skills                      | `.claude/skills/`                       |

---

## Open questions

Unanswered questions that block forward motion. Each should be closed in `docs/decisions/` when resolved.

- What is the first product? (Not "category" — the specific piece.)
- What is the brand mark — wordmark, logotype, both, neither?
- Is the site a store, a manifesto, or both? If both, which leads?
- How is sizing communicated without gendered language?
- What is the Hindi line on the home page?

---

## Standing cadence

| Cadence   | Action                                                    |
| --------- | --------------------------------------------------------- |
| Weekly    | Review `COMMAND_CENTER.md`. Move items. Add open questions. |
| Bi-weekly | Review `PROJECT_OPERATING_SYSTEM.md`. Change nothing unless there's a written argument. |
| Monthly   | Archive completed items from `Active` / `Next` into `docs/decisions/`. |
| Per drop  | Run `PLAYBOOK_LIBRARY.md → Playbook 01`.                  |

---

## Shortcuts for Claude

Common requests and where to point Claude:

- _"Write product copy"_ → `templates/product-copy.md` + `CLAUDE.md` tone rules.
- _"Write a caption"_ → `templates/caption.md` + `CLAUDE.md` tone rules.
- _"Draft a reply to a press request"_ → `PLAYBOOK_LIBRARY.md → Playbook 03`.
- _"Review this copy"_ → `CLAUDE.md` tone rules, then `PROJECT_OPERATING_SYSTEM.md` decision framework.
- _"Generate a new drop plan"_ → `PLAYBOOK_LIBRARY.md → Playbook 01`.
