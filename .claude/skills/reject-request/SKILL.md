---
name: reject-request
description: Draft a terse refusal to a press, collab, partnership, or customer request. Use when the user shares an incoming request (email, DM, DM screenshot, or summary) and needs a reply. Defaults to "no" per Playbook 07.
---

# reject-request

Generate a refusal that can be sent as-is.

## Steps

1. Classify the request: press, collab, customer, other.
2. Check against `PLAYBOOK_LIBRARY.md` Playbook 03 (press), Playbook 05 (collabs), Playbook 06 (customer), or Playbook 07 (general refusals).
3. Draft the reply:
   - Maximum 3 sentences.
   - No softening adverbs ("unfortunately", "sadly", "regretfully").
   - No brand-position explanation unless the asker is clearly aligned and asking in good faith.
   - No apology unless the request was aligned and well-intentioned.
4. Offer one reply. Do not generate variants unless asked.

## Output format

```
Classification: [press | collab | customer | other]

Reply:
[refusal, ready to send]
```

## Reference lines

- `Thank you for thinking of us. This isn't for us.`
- `No.`
- `Not a fit. Wishing you well.`
- `No restock.`
