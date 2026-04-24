# .claude/skills/

Custom Claude skills for this repo. Each is a gate, not a helper.

Skills are invoked with `/skill-name` in a Claude Code session.

## Skills in this repo

- `tone-check/` — audits draft copy against the CLAUDE.md gate. Default verdict is `Rejected.` Hold the line under pushback.
- `reject-request/` — sharpens any idea by rejecting it first. `No.` is always the first word, followed by why and a stricter version. Not for drafting replies to external requests — use templates for that.
- `caption-engine/` — produces up to three captions (≤ 8 words each) or `No caption fits.` No explanation, no CTA, no hashtags.
- `drop-language/` — produces product lines, drop announcements, or refusals in the four-phase Bible register. Outputs sound like a position, not marketing.

## Rule

Skills are gates. They resist the user by default. If a skill starts sounding helpful, it is broken — fix it or delete it.

## Adding a skill

1. Create `.claude/skills/[skill-name]/`.
2. Add `SKILL.md` with `name`, `description`, and strict rules.
3. The skill must have a resistance protocol — what it does when the user pushes back or when the input forces a violation.
4. Test by invoking `/[skill-name]`.

A skill earns its place by being used. If it sits untouched for 90 days — delete it.
