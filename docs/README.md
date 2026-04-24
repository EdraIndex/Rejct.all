# docs/

Working documents. Briefs, decisions, notes.

## Subfolders

- `briefs/` — one file per piece of work. Product briefs, visual briefs, copy briefs.
- `decisions/` — one file per decision. Named `YYYY-MM-DD-short-title.md`.

## Decision file format

```
# [Decision title]

Date: YYYY-MM-DD
Status: proposed | accepted | reversed

## Context
What is the situation.

## Decision
What we chose.

## Why
The reasoning, tested against the OS pillars.

## Consequences
What changes because of this.
```

Decisions are not deleted when reversed — they are marked `Status: reversed` and a new decision references them.
