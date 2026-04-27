---
type: voice
name: intuit-product-voice
applies_to: [errors, empty-states, onboarding, transactional, notifications, actions]
based_on: sources/synthesis/intuit-content-design-system.md
last_recompiled: 2026-04-27
---

# Voice: Intuit Product

**Persona (one sentence):** A calm, knowledgeable friend who respects your time, gives you only what you need right now, and never makes you feel dumb for asking.

---

## Core tone rules

1. **Conversational, not formal.** Write like you're talking to a smart friend, not filing a report.
2. **Active voice by default.** Passive only when softening blame on errors.
3. **Sentence case everywhere.** Headings, buttons, labels — all sentence case. No Title Case For Features.
4. **Contractions welcome.** "We'll," "can't," "you're." Not "ain't," "y'all," or noun contractions.
5. **Short sentences.** Under 20 words for most copy. Complex concepts get one extra sentence.
6. **No marketing voice inside the product.** "Amazing," "exciting," "delight" — homepage only.
7. **Acknowledge before fixing.** In errors: name what happened, then offer the next action.
8. **One task per screen.** Don't surface what they don't need yet.

---

## Things we never say

- "Oops!" / "Whoops!" / "Yikes!" — patronizing when someone's stuck
- "Error [code]" — jargon that confuses rather than helps
- "You entered the wrong X" — blames the user; say "That X didn't match"
- "We're sorry for the inconvenience" — hollow; be specific or skip the apology
- "Click here" — name the action: "View your invoice," not "Click here"
- "Please" in CTAs — passive; just state the action
- "Invalid," "prohibited," "restricted," "fraud," "suspended" — escalate anxiety unnecessarily

---

## Signature patterns

[[apology-then-fix]] [[error-message-structure]] [[verb-noun-cta]] [[empty-state-structure]] [[notification-urgency-tiers]] [[direct-bad-news]]

---

## Voice across surfaces

| Surface | Tone | Notes |
|---|---|---|
| Errors | Neutral → empathetic | Match severity; no humor; no blame |
| Empty states | Helpful, forward-looking | Invite action; avoid "nothing here" |
| Onboarding | Warm, confident | Quick wins; reduce overwhelm |
| Notifications | Functional, brief | Urgency-matched; don't over-notify |
| CTAs | Direct, action-forward | Verb + noun; 2–3 words; 24 char max |
| Bad news | Direct, calm, solution-focused | Upfront; don't dance around it |
| Celebrations | Warm, proportionate | 3 levels; don't over-celebrate |
| AI interactions | Transparent, brief | Always signal AI involvement |

---

## Intuit brand personality (applies to all product copy)

- **Forward thinking** — illuminate future opportunities, not just present state
- **Dynamic** — energetic, challenges norms, but not chaotic
- **Confident** — bold without arrogance; decisive language
- **Authentic** — approachable, kind, never corporate-speak
- **Driven** — advocate for the customer, even when the news is hard

---

## Top evidence strings

- (populate after `/wiki-ingest` runs on your shipped strings)
