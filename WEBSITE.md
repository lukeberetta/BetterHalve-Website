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
| `couple.png` | Lifestyle hero photo | Hero background |
| `01.png` | iPhone mockup — Home screen | Hero floating phone |
| `02.png` | iPhone mockup — Insights | Feature section 1 |
| `03.png` | iPhone mockup — Activity | Feature section 2 |
| `04.png` | iPhone mockup — Add Expense | Feature section 3 |
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

- Bold, editorial, dynamic — not a typical AI-template site
- Dieter Rams principles: minimal, purposeful, nothing decorative
- Rainbow.me inspired: dark bg, bright accent, large type, floating mockups
- Web3 aesthetic: glassmorphism nav, radial glows, scroll-driven animations
- PolySans Median for all headlines — tight tracking, large scale
- Phone mockups tilted and floating with CSS animations
- Scroll-triggered reveal animations via IntersectionObserver
- Hero parallax on `couple.png`
- Marquee strip between hero and features

---

## Page Structure (index.html)

1. **Nav** — fixed, transparent → frosted glass on scroll. Logo left, "Coming to App Store" pill right
2. **Hero** — full-viewport. `couple.png` parallax bg + gradient overlay. Headline left, `01.png` floating phone right
3. **Marquee** — scrolling feature strip (15+ currencies, AI insights, real-time sync, etc.)
4. **Features** — 3 alternating sections (phone + copy), each with a radial accent glow
5. **CTA card** — centered, dark raised card with bottom accent glow
6. **Footer** — logo + nav links + "Built in South Africa by Luke Beretta" credit

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
