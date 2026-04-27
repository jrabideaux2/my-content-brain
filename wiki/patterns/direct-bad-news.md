---
type: pattern
name: direct-bad-news
status: active
applies_to: [errors, transactional, notifications]
evidence_count: 0
avg_perf: {}
top_examples: []
last_lint: null
---

# Direct bad news

**Definition:** Deliver disappointing information upfront, in plain language, followed immediately by what the customer can do next. Never bury the news. Never dance around it.

**When to use:**
- Tax qualification denials
- Payment declines
- Feature sunsets or service interruptions
- Data loss or product failures
- Account suspensions or access issues
- Overcharges

**Structure:**
```
1. The news — direct, in the first sentence
2. What it means for them — one line if needed
3. What they can do — one clear action
```

**Tone rules:**
- Stay calm — don't escalate the customer's anxiety
- Take it seriously — don't minimize or joke
- Be transparent — enough to inform, not so much it confuses
- Empathize genuinely — acknowledge the impact on them
- Give them the benefit of the doubt — assume good intent

**DO:**
- Lead with the news directly: "Your payment didn't go through."
- Focus on solutions, not problems: what can they do right now?
- Be comforting and reassuring where possible

**DON'T:**
- Copy-paste generic responses
- Dance around the bad news
- Shift responsibility to the customer
- Exaggerate urgency unnecessarily
- Mention security concerns unless directly relevant (raises alarm)
- Use negative constructions: rewrite "can't" / "won't" / "don't" as what they *can* do
- Trivialize frustration
- Say "we're sorry" unless the error was Intuit's fault and caused real customer effort

**Example contrast:**
- ✓ "Your subscription ended on March 15. [Renew now] to keep access to your files."
- ✗ "We regret to inform you that your subscription has been terminated due to non-payment."

**Backlinks:** [[intuit-product-voice]] [[error-message-structure]] [[notification-urgency-tiers]] [[never-blame-user]]
