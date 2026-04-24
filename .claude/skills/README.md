# .claude/skills/

Custom Claude skills for this repo.

Skills are invoked with `/skill-name` in a Claude Code session. Each skill is a folder containing a `SKILL.md` that defines when Claude should trigger it and what it should do.

## Seeded skills

- `tone-check/` — runs any draft through Rejct.all tone rules
- `reject-request/` — drafts a terse refusal per Playbook 07

## Adding a skill

1. Create a folder: `.claude/skills/[skill-name]/`.
2. Add `SKILL.md` with `name`, `description`, and the instructions.
3. Test it by invoking `/[skill-name]` in a session.

A skill earns its place by being used. If a seeded skill sits untouched for 90 days, delete it.
