---
type: pattern
name: empty-state-structure
status: active
applies_to: [empty-states]
evidence_count: 0
avg_perf: {}
top_examples: []
last_lint: null
---

# Empty state structure

**Definition:** Empty states follow a three-part structure — headline, optional body, optional CTA — and always serve one of three purposes: orient the user, inspire action, or celebrate completion.

**When to use:**
- First-time use: feature never yet engaged with
- No data: content deleted, search returned nothing
- Task completion: inbox zero, no pending items, cleared queue

**Three scenarios and their approach:**

### First-time use
- Orient: tell them what will appear once they start
- Inspire: one clear action to get going
- Example: "When you have bills ready to review, you'll find them here."

### No data / failed search
- Be helpful — don't dead-end
- Suggest a refinement or a path forward
- Example: "No results for 'payroll'. Try 'payments' or [browse categories]."

### Task completion / zero state achieved
- Celebrate appropriately (see [[celebrate-sparingly]])
- Point to what's next — don't leave them stranded in success
- Example: "You're all caught up! Check your profit and loss report."

**Four principles (Intuit):**

1. **Be clear.** Plain language. What happened, what comes next. No jargon.
2. **Be helpful.** Positive tone. Give them a way forward.
3. **Keep it brief.** Cut details that don't help them act.
4. **Inspire action.** Guide them toward the next step; don't describe the emptiness.

**Structure:**
```
Headline: Clear, one line — what's true right now or what to do
Body: [optional] One sentence expanding on headline — benefit, not repetition
CTA: [optional] Primary action; secondary action only if genuinely needed
```

**Strong examples:**
- ✓ "Upload your first report"
- ✓ "You're all caught up!"
- ✓ "When you have bills ready to review, you'll find them here."
- ✗ "[No message]" — leaves users stranded
- ✗ "No results found" — dead-end; provide a path

**What to avoid:**
- Never say "Nothing here yet" without a path forward
- Don't celebrate routine or daily completions — use sparingly
- Don't use empty states to push marketing messages

**Backlinks:** [[intuit-product-voice]] [[empty-state-invitation]] [[celebrate-sparingly]] [[verb-noun-cta]]
