# Mintlify Landing Page

Peer-review assignment for **ChaiCode Cohort 2026** as part of learning HTML & CSS. This landing page is designed purely using **vanilla CSS** (no CSS frameworks).

---

## Live URL

<!-- Add your deployed link here -->
**Live URL:** _[Add your live URL here]_

> **Tip:** For the best viewing experience, open the URL in your browser with **zoom set to 100%**.

---

## Sections Recreated

| Section | Description |
|--------|-------------|
| **Header / Navigation** | Mintlify logo, nav links (Resources, Documentation, Customers, Blog, Pricing), and CTA buttons (Contact Sales, Start for free) |
| **Hero** | “New” badge (Self-updating docs), main headline “The Intelligent Knowledge Platform”, subheading, email signup form, and hero illustration |
| **Trusted by (Brands)** | Logo strip featuring Anthropic, Coinbase, Microsoft, Perplexity, HubSpot, X, PayPal, Lovable |
| **Feature highlights** | “Built for the intelligence age” with three feature blocks: **LLMs>TXT & MCP**, **AGENT**, and **ASSISTANT**, each with supporting copy and video |
| **Enterprise** | “Bring intelligence to enterprise knowledge” with feature cards (Build with Partnership, Compliance and access control), Anthropic customer story banner, and company logos |
| **Customers / Case studies** | “Unlock knowledge for any industry” with a horizontal carousel of customer cards (Perplexity, X, Kalshi, Cognition) and carousel controls |
| **End CTA** | “Make documentation your winning advantage” with Get started / Get a demo buttons and two CTA cards (Pricing on your terms, Start building) |
| **Footer** | Mintlify logo, social links (LinkedIn, X, GitHub), Explore / Resources / Documentation / Company / Legal link groups, security badge, and copyright |

---

## Fonts Used

- **Body / UI:** System font stack — `system-ui`, `-apple-system`, `BlinkMacSystemFont`, `Segoe UI`, `Roboto`, `Oxygen`, `Ubuntu`, `Cantarell`, `Open Sans`, `Helvetica Neue`, `sans-serif`
- **Labels / small headings (e.g. “NEW”, “AGENT”, “ENTERPRISE”):** `monospace`

---

## Colors Used

Defined in `style.css` via CSS custom properties (`:root`):

| Variable | Hex | Usage |
|----------|-----|--------|
| `--primary-font-color` | `#FFFFFF` | White text (hero, banners) |
| `--secondary-font-color` | `#000000` | Black text, primary buttons |
| `--text-hover-color` | `#195C7C` | Nav hover, Contact Sales |
| `--button-hover-color` | `#2D2D2E` | Button hover state |
| `--new-cta` | `#094C6A` | “New” badge background |
| `--new-cta-hover` | `#0B5474` | “New” badge hover |
| `--new-cta-background` | `#0C8C5E` | Green accent (labels, links) |
| `--email-cta-background` | `#71B2A8` | Email form background |
| `--email-cta-border` | `#e5e7eb3b` | Email form border |
| `--email-cta-placeholder` | `#B8D9D6` | Input placeholder |
| `--font-subheading` | `#585858` | Muted body text |
| `--footer-outline` | `#EDEDED` | Footer borders |

Additional colors used in the layout: `#E8E8E8` (card borders), `#F8F8F8` (enterprise section background), `#a8a8a8`, `#807d7d`, `#808081` (muted text).

---

## Screenshot

<img width="1920" height="1164" alt="mintlify" src="https://github.com/user-attachments/assets/7520cb56-4d29-41a8-856e-238c454c5fcb" />

---

## Project structure

```
Mintlify Landing Page/
├── index.html          # Main HTML structure
├── style.css           # Vanilla CSS styles
├── README.md           # This file
└── assets/
    ├── logo.svg, banner.svg, hero-image-light.svg, bg-light.svg, etc.
    ├── brand-logos/    # Company logos
    ├── carousel-cards/ # Customer card images
    └── videos/         # Feature demo videos
```

---

## How to run locally

1. Clone or download this folder.
2. Open `index.html` in a browser(VS Code Live Server).
3. Use **100% zoom** in the browser for the intended layout.

---
*ChaiCode Cohort 2026: HTML & CSS Peer Review*