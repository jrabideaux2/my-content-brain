---
type: pattern
name: notification-urgency-tiers
status: active
applies_to: [notifications]
evidence_count: 0
avg_perf: {}
top_examples: []
last_lint: null
---

# Notification urgency tiers

**Definition:** Every notification is assigned a urgency level — low, medium, or high — and the copy tone, frequency, and channel choice must match that tier.

**When to use:**
- Before writing any notification (in-product, push, or SMS), assign a tier first. The tier determines tone and how much real estate the message deserves.

**The three tiers:**

### Low urgency — informational
- New features, app improvements, completed background tasks
- Tone: calm, matter-of-fact
- Channel: in-product only; batch these
- Example: "Your report is ready to download."

### Medium urgency — encouraging
- Milestones, celebrations, opportunities, helpful nudges
- Tone: warm, positive
- Channel: in-product; push only if timely
- Example: "You've hit your savings goal for March. Keep it going."

### High urgency — action required
- Time-sensitive actions: payment due, account access issue, legal deadline
- Tone: direct, clear resolution path — neutral, not alarming
- Channel: push, SMS if appropriate; send once
- Example: "Update your billing info by 3/22 to keep your subscription active."

**Rules for all tiers:**
- Less is more — don't bombard customers
- Ask before sending: Is this the right channel? What's the customer benefit? Is this the right moment in their workflow?
- Avoid sensitive data visible on a lock screen (push)
- Avoid late night / early morning sends (respect time zones)
- Use emoji sparingly — only when culturally safe and accessible
- Celebrate wins promptly; deliver bad news directly with next steps
- If push notifications cause opt-outs, they failed

**What not to do:**
- Send low-urgency content as high-urgency (cried-wolf effect)
- Batch medium/high urgency messages — timing matters
- Treat every feature update as a notification-worthy event

**Backlinks:** [[intuit-product-voice]] [[direct-bad-news]] [[celebrate-sparingly]]
