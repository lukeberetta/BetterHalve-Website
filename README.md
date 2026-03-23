# BetterHalve — Website

Marketing site for [BetterHalve](https://betterhalve.com), the shared expense app built for couples. Track spending, split costs, and settle up effortlessly.

Deployed on **Cloudflare Pages**, synced directly from this repo. No build step — pure static HTML, CSS, and JS.

---

## Pages

| File | URL |
|---|---|
| `index.html` | `/` — Main landing page |
| `support.html` | `/support` — FAQ + contact |
| `privacy.html` | `/privacy` — Privacy policy |
| `terms.html` | `/terms` — Terms of use |

## Structure

```
/
├── index.html
├── support.html
├── privacy.html
├── terms.html
├── fonts/
│   ├── PolySans-Median.ttf    # 600 — headlines, nav, buttons
│   └── PolySans-Neutral.ttf   # 400 — body copy
└── img/
    ├── couple.png             # Hero background
    ├── 01–04.png              # iPhone mockups
    ├── logo.svg               # Horizontal wordmark
    └── app icon.svg
```

## Deployment

Push to `main` → Cloudflare Pages builds and deploys automatically.

No dependencies. No build step. Nothing to install.

---

Built in South Africa by [Luke Beretta](https://lukeberetta.com).
