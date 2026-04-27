---
type: pattern
name: error-message-structure
status: active
applies_to: [errors]
evidence_count: 0
avg_perf: {}
top_examples: []
last_lint: null
---

# Error message structure

**Definition:** Every error message follows a three-part structure: (1) headline — what happened or what to do; (2) more info — optional additional context; (3) call to action — one concrete next step.

**When to use:**
- Any UI error state: payment failure, network issue, form validation, permission denied, system outage.
- Scale complexity to severity: minor errors may only need headline + CTA; severe errors warrant all three parts.

**When NOT to use:**
- Inline field validation: use just the corrective label (e.g., "Email format: name@domain.com") — no headline needed.
- Toast notifications: headline + optional CTA only; no room for body copy.

**Structure:**

```
Headline: What happened or what to do (plain language, no jargon)
More info: [optional] One sentence of context — if the user needs it to act
CTA: One action. Link to support if self-service isn't possible.
```

**Severity tiers and tone:**

| Severity | Example | Tone |
|---|---|---|
| Minor | Wrong password | Casual, conversational |
| Moderate | Payment declined | Neutral, direct |
| Severe | Data loss, service outage | Neutral, empathetic — never dismissive |

**Real examples (Intuit):**

- ✓ "Check your internet connection. You're not connected right now. [Retry]"
- ✗ "Network connection error. The server connection has failed."
- ✓ "Your account is connected, but your forms aren't ready yet. [Get help]"
- ✗ "Forms not ready (902)"

**Key rules:**
- Avoid error codes in user-facing copy
- Never use: error, invalid, prohibited, fail, denied, fraud, suspended
- Never use: whoops, oops, hmm, yikes
- Use passive voice only to soften blame: "The card was declined" not "You entered a bad card"
- One CTA only; if self-service isn't available, link to support

**Backlinks:** [[intuit-product-voice]] [[apology-then-fix]] [[never-blame-user]] [[avoid-error-jargon]]
