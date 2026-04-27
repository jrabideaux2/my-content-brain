---
type: theme
name: global-readability
status: active
applies_to: [errors, empty-states, onboarding, transactional, notifications, actions]
evidence_count: 0
top_examples: []
last_lint: null
---

# Theme: Global readability

**Definition:** Copy written to survive translation, localization, and reading by non-native English speakers — without becoming robotic or losing brand personality.

**Why this theme matters:** Intuit operates globally. Romance languages require ~30% more space than English. Word order varies dramatically across languages. Idioms, contractions, and cultural metaphors often break entirely in translation. Writing for global readability also benefits every native English reader — it forces precision.

---

## Core rules (Intuit)

- **Sentences under 20 words.** Long sentences are harder to translate and harder to scan.
- **Lines under 80 characters.** Especially important for screen readers and small-viewport designs.
- **Consistent terminology.** If you call it "invoice" in one place, call it "invoice" everywhere. Synonyms confuse translators and users.
- **Avoid idioms.** "Hit the ground running," "on the same page," "low-hanging fruit" — these don't translate. Write what you mean.
- **Manage contractions.** Everyday contractions (we'll, can't, you're) are fine. Unusual ones are risky. Avoid regional variants (ain't, y'all).
- **Gender neutrality helps translation.** Many Romance languages require gendered nouns. Writing in second person ("you") sidesteps this entirely.
- **Avoid metaphors untested cross-culturally.** Financial metaphors especially — what "bounced check" means is not universal.

---

## Translation-specific flags

Before handing copy to localization, check:
- Any idiom or culturally-specific phrase
- Any sentence over 20 words
- Any term that has been used inconsistently across screens
- Any gendered pronoun that could be rewritten in second person
- Any reference to a US-specific institution, law, or product that won't exist in other markets

---

## Numbers, dates, and currency

- Format dates as month-day-year for US; confirm locale format before shipping globally
- Spell out currency symbols where ambiguous: "$500" works in the US; "USD 500" is safer cross-border
- Avoid ordinal abbreviations (1st, 2nd) — spell them out or use numerals only

**Backlinks:** [[intuit-product-voice]] [[accessibility]] [[inclusivity]]
