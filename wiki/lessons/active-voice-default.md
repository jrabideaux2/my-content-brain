---
type: lesson
name: active-voice-default
applies_to: [errors, empty-states, onboarding, transactional, notifications]
severity: hard
source_event: intuit-content-design-system
last_violated: null
---

# Active voice is the default

**Rule:** Write in active voice. Subject → verb → object. Passive voice is allowed only in two specific situations.

**Why:** Active voice is clearer, more conversational, and faster to parse. It names who's doing what, which reduces ambiguity — especially important for multilingual users and screen readers.

**How to apply:**
- ✓ "We couldn't save your changes." → active, names the actor (we)
- ✗ "Your changes weren't saved." → passive, buries the actor

**Two permitted uses of passive voice:**
1. Softening a user-caused error: "The card was declined by your bank" shifts focus away from the user's action.
2. Confirmation messages where the actor is obvious: "Payment submitted." is acceptable shorthand.

**Test:** If you can add "by zombies" after the verb and it makes grammatical sense, it's passive and should be rewritten.
- "Your changes weren't saved [by zombies]" — passive ✗
- "We couldn't save your changes" — can't add zombies ✓
