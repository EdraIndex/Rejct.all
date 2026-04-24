# Respond to an incoming request

## Purpose
Draft a reply to a press, collab, partner, or customer request. Classify first, then reply per the relevant playbook.

## Input
- Request type (press, collab, customer, other)
- Verbatim request if available
- Tone of reply (neutral, warmer, firm)

## Prompt

```
Classify and draft a reply for rejct.all. Follow CLAUDE.md voice rules, PLAYBOOK_LIBRARY.md (03 for press, 04 for collabs, 05 for customers, 06 for refusals), and Brand Bible §12 for press policy.

Important: the Bible does not default to refusing press. It refuses paid placement and advertorials specifically. Editorial from aligned outlets is on the table. PR seeding to selected individuals is allowed (no paid placement).

Request type: [press / collab / customer / other]
Request: [paste request or summarize]
Tone: [neutral / warmer / firm]

Produce:
1. Classification (one line).
2. Decision: accept, decline, or clarify.
3. Reply (ready to send).

Constraints:
- Maximum 6 short lines.
- No softening adverbs ("unfortunately", "sadly").
- No exclamation points.
- Brand name lowercase.
- No position explanation unless asker is aligned and asking in good faith.
```

## Output expectations
- A reply that could be sent as-is.
- Paid / advertorial / celebrity seeding → decline with `Not a fit. Wishing you well.`
- Aligned editorial → accept, with constraints (written Q&A, no tech-pack sharing).
- Aligned individual seeding request → accept with a short, no-brief note.
- Customer → route through Playbook 05 templates.
