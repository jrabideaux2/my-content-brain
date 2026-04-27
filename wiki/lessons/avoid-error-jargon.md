---
type: lesson
name: avoid-error-jargon
applies_to: [errors]
severity: hard
source_event: intuit-content-design-system
last_violated: null
---

# No jargon or error codes in user-facing error messages

**Rule:** Never show error codes, technical status codes, or jargon terms in user-facing error messages. Translate everything into plain language.

**Why:** Error codes like "(902)" and terms like "invalid," "prohibited," or "server connection failed" tell the user nothing actionable. They escalate anxiety and make users feel the product is broken. Plain language tells them what happened and what to do.

**How to apply:**
- ✓ "Your account is connected, but your forms aren't ready yet. [Get help]"
- ✗ "Forms not ready (902)"
- ✓ "Check your internet connection. You're not connected right now."
- ✗ "Network connection error. The server connection has failed."

**Words to remove from error copy:**
- error, invalid, prohibited, restricted, fail/failed, denied, fraud, suspended
- Any HTTP status codes (403, 500, etc.)
- Any internal error codes
- Technical system names

**When you have no information:** "Something went wrong. Try again, or [contact support] if it keeps happening." — vague is better than jargon.
