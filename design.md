# Design Tokens — Colors

Defined in [`styles.css`](styles.css) under `:root`. All pages (including the Thai versions in `th/`) share this single stylesheet, so changing a value here updates the whole site.

| Variable | Value | Usage |
|---|---|---|
| `--primary` | `#E0A800` | Primary accent — buttons, links, icons, highlighted text |
| `--primary-dark` | `#8A6800` | Hover/active states, darker accent text |
| `--primary-tint` | `#FBF3D9` | Light accent background (badges, tags) |
| `--primary-tint-2` | `#F5DE8E` | Secondary accent background/border |
| `--ink` | `#221E1B` | Primary text color |
| `--ink-soft` | `#5C5650` | Secondary/muted text |
| `--paper` | `#FFFFFF` | Default page background |
| `--paper-warm` | `#FBF8F4` | Warm section background (alternating sections) |
| `--line` | `rgba(34, 30, 27, 0.1)` | Subtle borders/dividers |
| `--line-strong` | `rgba(34, 30, 27, 0.18)` | Stronger borders (e.g. outlined buttons) |

## Fonts

Defined in [`styles.css`](styles.css) (English pages) and [`th/thai-fonts.css`](th/thai-fonts.css) (Thai pages, loaded after `styles.css` to override).

| Font | Usage | Pages |
|---|---|---|
| Space Grotesk | Headings (`h1`–`h4`), brand, buttons, nav | EN (fallback for TH) |
| Inter | Body text | EN (fallback for TH) |
| JetBrains Mono | `.mono`, eyebrow labels, stat numbers | EN (fallback for TH) |
| Noto Sans Thai | All text — body, headings, mono/labels | TH only, takes priority over the EN fonts above |

## Other tokens

| Variable | Value | Usage |
|---|---|---|
| `--radius` | `14px` | Default corner radius (cards, buttons) |
| `--radius-sm` | `8px` | Small corner radius (tags, badges) |
| `--maxw` | `1120px` | Max content width |

## Notes

- To retheme the site, edit the four `--primary*` values in `styles.css:4-7`.
