# Project Rules

## When to apply each ruleset
- Working on UI/components → follow @.claude/design-rules.md
- Reviewing a design/PR → follow @.claude/design-review.md
- Building features/writing code → follow @.claude/build-code.md

## Figma
- **File key**: `wGuiIwIAHBXQoW8LudaBcz` (SOLA)
- **Design page**: `Designs` — all new UI screens go here
- **Token reference**: variables are live in the Figma file; source JSON is in `tokens/`
- **Semantic token usage**: follow @.claude/semantic-usage.md
- **Typography**: use text styles `heading/*`, `body/*`, `caption/*`, `tabular/*` — never hardcode font properties

## When designing in Figma
1. Always target the `Designs` page (switch with `await figma.setCurrentPageAsync(...)`)
2. Use semantic color variables from the `Semantic/New` collection (Light mode by default)
3. Use `Raw/spacing` variables for all padding, gap, margin values
4. Use `Raw/border-radius` variables for corner radii
5. Apply text styles from `figma.getLocalTextStyles()` — match by name (e.g. `body/base`)
6. Take a screenshot after each major section to verify before continuing
