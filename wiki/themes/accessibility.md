---
type: theme
name: accessibility
status: active
applies_to: [errors, empty-states, onboarding, transactional, notifications, actions]
evidence_count: 0
top_examples: []
last_lint: null
---

# Theme: Accessibility

**Definition:** Content and UI designed to be perceivable, operable, understandable, and robust across all vision levels, cognitive abilities, motor differences, and assistive technologies. Built on the POUR framework.

**Why this theme matters:** Accessibility isn't a feature or a compliance checkbox — it's a baseline. If a screen reader can't parse the page, or contrast is too low for a user with low vision, the product fails those customers entirely.

---

## POUR framework (Intuit)

### Perceivable
Users must be able to process all screen content.
- Include meaningful alt text for images, icons, and controls
- Caption videos with speaker identification, synchronized
- Don't put text in images (if meant to be read)
- Provide text alternatives (data tables) for charts and graphs
- Verify sufficient foreground-to-background contrast
- Don't rely solely on color for status indicators — pair with icons or text
- Ensure visible focus indicators on all interactive elements

### Operable
Interactions must be accessible and easy to target.
- Keep field labels visible during input (no ghost-text-as-label)
- Follow logical tab order
- Communicate validation timing and error message placement
- Present errors with visual indicators beyond color alone

### Understandable
Content must be simple, direct, and predictable.
- Aim for **5th to 8th grade readability** (Flesch-Kincaid)
- Sentences under ~20 words; lines under 80 characters
- Create unique, informative page titles
- Maintain consistent heading styles and proper HTML hierarchy (H1, H2...)
- Use headings, subheadings, and bullets for scannability
- Don't use ghost text in place of a field label

### Robust
Content must function across platforms, browsers, devices, and assistive tech.
- Use platform-agnostic language: "Select all that apply" not "Tap here" or "Click here"
- Test with actual screen readers, not just automated checks

---

## Content design flags to raise

When reviewing designs, flag:
- Non-standard icons with no text label
- Complex interactions not navigable by keyboard
- Background images without alt text
- Charts or infographics without a text alternative
- Ghost text used instead of a proper label
- Videos without captions
- Lines exceeding 80 characters
- Links that are color-only (no underline or other distinction)

**Backlinks:** [[intuit-product-voice]] [[error-message-structure]] [[verb-noun-cta]]
