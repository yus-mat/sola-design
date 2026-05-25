# Semantic Token Usage Guide

Reference when choosing color tokens for UI design. Always prefer semantic tokens over raw colors.
Collection in Figma: `Semantic/New` · Light mode by default.

---

## Surface vs Background

| Token | Use for |
|---|---|
| `surface/Default` | Page canvas — the outermost background (white in light) |
| `surface/Muted` | Slightly recessed areas: sidebars, off-canvas panels |
| `surface/Raise` | Elevated layers: cards, modals, dropdowns floating above surface |
| `background/Primary` | Main content area fill |
| `background/Secondary` | Secondary section fill (slightly off-white) |
| `background/Muted` | Inactive, skeleton, or disabled area fills |

---

## Background — Action (buttons)

| Token | Use for |
|---|---|
| `background/Action/Primary-Default` | Primary button default fill |
| `background/Action/Primary-Hover` | Primary button hover fill |
| `background/Action/Primary-Pressed` | Primary button pressed/active fill |
| `background/Action/Secondary-Default` | Secondary (outline) button fill — transparent in light |
| `background/Action/Secondary-Hover` | Secondary button hover fill |
| `background/Action/Secondary-Pressed` | Secondary button pressed fill |
| `background/Action/Danger-Default` | Destructive button default |
| `background/Action/Danger-Hover` | Destructive button hover |
| `background/Action/Danger-Pressed` | Destructive button pressed |

---

## Background — Interactive (rows, list items, selectable areas)

| Token | Use for |
|---|---|
| `background/Interactive/Default` | Table row / list item default state |
| `background/Interactive/Hover` | Table row / list item hover state |
| `background/Interactive/Pressed` | Table row / list item pressed/selected state |

---

## Background — Semantic states (banners, alerts, field backgrounds)

| Token | Use for |
|---|---|
| `background/Error` | Error field background, error banner tint |
| `background/Success` | Success banner tint |
| `background/Warning` | Warning banner tint |
| `background/Info` | Info banner tint |
| `background/Accent` | Accent/highlight tint (purple) |

---

## Text

| Token | Use for |
|---|---|
| `text/Primary` | Body text, headings, labels |
| `text/Secondary` | Supporting text, metadata, captions |
| `text/Muted` | Placeholder, hint, disabled text |
| `text/Inverse` | Text on dark or colored backgrounds |
| `text/Action` | Clickable text, links |
| `text/Error` | Inline error messages |
| `text/Success` | Success confirmation text |
| `text/Warning` | Warning text |
| `text/Info` | Info text |
| `text/Accent` | Accent-colored text (purple) |

---

## Border

| Token | Use for |
|---|---|
| `border/Primary` | Strong dividers, focused input borders |
| `border/Secondary` | Default input/card borders |
| `border/Muted` | Subtle section dividers |
| `border/Inverse` | Borders on dark backgrounds |
| `border/Action` | Focused interactive element border |
| `border/Error` | Error state input border |
| `border/Success` | Success state border |
| `border/Warning` | Warning state border |
| `border/Info` | Info state border |
| `border/Accent` | Accent border (purple) |

---

## Spacing quick-reference (Raw/spacing)

| Token | px | Common use |
|---|---|---|
| `spacing/1` | 4px | Icon gap, tight padding |
| `spacing/2` | 8px | Small padding, compact gap |
| `spacing/3` | 12px | Input inner padding (vertical) |
| `spacing/4` | 16px | Standard padding, card inner |
| `spacing/5` | 20px | Section gap |
| `spacing/6` | 24px | Large padding |
| `spacing/8` | 32px | Section spacing |
| `spacing/10` | 40px | Page-level spacing |
| `spacing/12` | 48px | Hero padding |

---

## Border radius quick-reference (Raw/border-radius)

| Token | px | Common use |
|---|---|---|
| `radius/sm` | 2px | Tags, badges, chips |
| `radius/base` | 4px | Inputs, small buttons |
| `radius/md` | 6px | Medium components |
| `radius/lg` | 8px | Cards, modals |
| `radius/xl` | 12px | Large cards, dialogs |
| `radius/full` | 9999px | Pills, avatars, toggle knobs |
