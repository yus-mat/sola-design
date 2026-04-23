# Design System Rules

## Typography — Always use these tokens, never hardcode font sizes. All font sizes and line heights must use CSS custom properties defined in `src/styles/typography.css`.


| Token | Family | Size | Line Height | Weight |
|-------|--------|------|-------------|--------|
| heading-xlg | Noto Sans JP | 40px | 48px | 700 (Bold) |
| heading-lg | Noto Sans JP | 32px | 40px | 700 (Bold) |
| heading-md | Noto Sans JP | 28px | 36px | 700 (Bold) |
| heading-sm | Noto Sans JP | 24px | 32px | 700 (Bold) |
| body-lg | Noto Sans JP | 18px | 28px | 400 (Regular) |
| body-lg-bold | Noto Sans JP | 18px | 28px | 700 (Bold) |
| body-base | Noto Sans JP | 16px | 24px | 500 (Medium) |
| body-base-bold | Noto Sans JP | 16px | 24px | 700 (Bold) |
| body-sm | Noto Sans JP | 14px | 20px | 400 (Regular) |
| body-sm-bold | Noto Sans JP | 14px | 20px | 700 (Bold) |
| caption | Noto Sans JP | 12px | 16px | 400 (Regular) |
| caption-bold | Noto Sans JP | 12px | 16px | 700 (Bold) |
| tabular | IBM Plex Mono | 14px | 20px | 400 (Regular) |

## Rules
- Never hardcode font sizes like `font-size: 14px`
- Always reference the CSS variable or token name above
- Bold variants use `font-weight: 700`, medium use `font-weight: 500`, regular use `font-weight: 400`
- Heading tokens are always bold (700) — never use them at lower weights
- `body-base` / `body-base-bold` is the standard body size (16px), not `body-md`
- `tabular` uses IBM Plex Mono for numeric/monospace content
