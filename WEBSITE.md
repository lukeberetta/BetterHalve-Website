# BetterHalve Website

Landing page for the BetterHalve iOS app, deployed via Cloudflare Pages (synced from GitHub).

---

## Pages

| File | Purpose |
|---|---|
| `index.html` | Main landing page |
| `support.html` | Support — FAQ accordion + contact |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of use |

---

## Assets

### Fonts (`/fonts/`)
| File | Weight | Usage |
|---|---|---|
| `PolySans-Median.ttf` | 600 | Headlines, nav, buttons |
| `PolySans-Neutral.ttf` | 400 | Body copy, metadata |

### Images (`/img/`)
| File | Description | Used in |
|---|---|---|
| `couple.jpg` | Lifestyle photo | Unused |
| `01.png` | iPhone mockup — Home screen | Hero phone |
| `02.png`–`04.png` | iPhone mockups — Insights, Activity, Add Expense | Unused |
| `logo.svg` | Horizontal wordmark | Nav, footer |
| `logo stacked.svg` | Stacked wordmark | Available if needed |
| `app icon.svg` | App icon | Available if needed |

---

## Brand Tokens

| Token | Hex | Usage |
|---|---|---|
| `--bg` | `#160d0b` | Page background |
| `--bg-mid` | `#2E1714` | Section backgrounds, marquee |
| `--bg-raised` | `#3A1E1A` | Cards |
| `--text` | `#FFDCCC` | Primary text |
| `--text-muted` | `#8A5E58` | Secondary text, metadata |
| `--accent` | `#FB591B` | CTAs, highlights, eyebrows |
| `--accent-soft` | `#F2A58E` | Subtitles, soft accents |
| `--positive` | `#7DC88A` | Available for positive states |

Font stack: `'PolySans', -apple-system, BlinkMacSystemFont, sans-serif`

---

## Design Direction

- Minimal, single-screen landing page — nothing decorative
- Dark bg, one accent colour, large PolySans Median headline with tight tracking
- One static phone mockup, no tilts, glows, parallax or scroll animations

---

## Page Structure (index.html)

1. **Nav** — logo left, "Download" link right
2. **Hero** — headline, one-line subtitle, App Store badge; `01.png` phone on the right (stacked below on mobile)
3. **Footer** — single line: credit left, Support / Privacy / Terms right

---

## Legal Pages

Both `privacy.html` and `terms.html` share the nav/footer design with a simplified single-column content layout.

Privacy policy source: provided by Luke Beretta (original for BetterHalf app, updated to BetterHalve).
Contact for data requests: hello@lukeberetta.com

---

## Deployment

- Hosted on Cloudflare Pages
- Synced from GitHub (push to deploy)
- No build step — pure static HTML/CSS/JS
