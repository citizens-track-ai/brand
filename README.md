# Citizens' Track on AI — Brand Kit & Guidelines

This directory contains the official brand assets, design specifications, and implementation tokens for **Citizens' Track AI** (Version 1.0, October 2026).

It is structured so that AI agents, developers, and designers working on other projects (websites, dashboards, slide decks, newsletters) can easily copy or link to these assets and apply the branding with 100% fidelity.


## ⚖️ Brand Asset Usage & Permissions

The Citizens’ Track on AI name, emblem, and logo marks are held by and for the Citizens’ Track on AI initiative.

Permitted Use: Partners, researchers, community assembly organizers, and media are welcome to use these brand assets to accurately reference, report on, or promote official Citizens' Track AI events, tools, and research, provided the brand guidelines in this repository are followed.

Restrictions: You may not modify, alter, or adapt the logo or emblem, nor use them in any manner that implies official endorsement, sponsorship, or partnership without prior written consent. Brand assets may not be used for commercial merchandise or unrelated commercial products.

Inquiries & Approvals: For questions, custom permissions, or co-branding requests, please contact the communications team at contact@citizens-track.org.

---

## 📖 Quick Links
- **[Full Brand Guidelines Specification](BRAND_GUIDELINES.md)** (`BRAND_GUIDELINES.md`) — In-depth guide detailing logo rules, color values, contrast rules, typography, iconography, and charts.
- **[CSS Design Tokens](brand-tokens.css)** (`brand-tokens.css`) — Ready-to-import CSS variables (`--ct-color-*`, `--ct-font-*`, `--ct-space-*`).
- **[JSON Design Tokens](brand-tokens.json)** (`brand-tokens.json`) — Machine-readable design tokens for design tools, build scripts, and JavaScript components.

---

## 🎨 Asset Catalog (`images/`)

### 1. Logos (`images/logos/`)
All logo variations are provided in pristine vector **SVG** (infinitely scalable, transparent background) and 300 DPI transparent **PNG**:

- **Wide (Primary):**
  - Positive (Light backgrounds): [SVG](images/logos/logo-wide-positive.svg) | [PNG](images/logos/logo-wide-positive.png)
  - Negative (Dark backgrounds): [SVG](images/logos/logo-wide-negative.svg) | [PNG](images/logos/logo-wide-negative.png)
  - Monochrome White: [SVG](images/logos/logo-wide-white.svg) | [PNG](images/logos/logo-wide-white.png)
  - Monochrome Black: [SVG](images/logos/logo-wide-black.svg) | [PNG](images/logos/logo-wide-black.png)
- **Stacked (Compact / Mobile):**
  - Positive: [SVG](images/logos/logo-stacked-positive.svg) | [PNG](images/logos/logo-stacked-positive.png)
  - Negative: [SVG](images/logos/logo-stacked-negative.svg) | [PNG](images/logos/logo-stacked-negative.png)
  - Monochrome White: [SVG](images/logos/logo-stacked-white.svg) | [PNG](images/logos/logo-stacked-white.png)
  - Monochrome Black: [SVG](images/logos/logo-stacked-black.svg) | [PNG](images/logos/logo-stacked-black.png)
- **Emblem Standalone (Favicons & Avatars):**
  - Positive: [SVG](images/logos/emblem-positive.svg) | [PNG](images/logos/emblem-positive.png)
  - Cerulean: [SVG](images/logos/emblem-cerulean.svg) | [PNG](images/logos/emblem-cerulean.png)
  - Coral: [SVG](images/logos/emblem-coral.svg) | [PNG](images/logos/emblem-coral.png)
  - White: [SVG](images/logos/emblem-white.svg) | [PNG](images/logos/emblem-white.png)
  - Favicon: [SVG](images/logos/favicon.svg) | [PNG](images/logos/favicon.png)

### 2. Brand Icons (`images/icons/`)
Each icon is available in standalone transparent **SVG** and 300 DPI transparent **PNG** across 8 official colourways (`cerulean/`, `teal/`, `coral/`, `goldenrod/`, `white/`, `ebony/`, `fjord/`, `redwood/`):

- **6 Core Subjects:**
  - `icon-globe-chart` (Global Deliberation & Analytics)
  - `icon-open-book` (Evidence Packs & Policy Education)
  - `icon-ai-network` (AI Synthesis & Structured Tech Grid)
  - `icon-journey-map` (Citizen Roadmap & Waypoints)
  - `icon-shield-cubes` (Privacy, Security & Data Guardrails)
  - `icon-sentiment-gauge` (Community Sentiment & Polling)
- **Original Cards on Fjord Blue:** Available in [images/icons/cards/](images/icons/cards/) (including [icons-grid.png](images/icons/cards/icons-grid.png)).

### 3. Visual Guidelines Reference (`images/guidelines/`)
High-resolution captures of the official PDF brand manual pages for instant visual review:
- Cover: [guidelines-cover.png](images/guidelines/guidelines-cover.png)
- Logo Elements: [logo-elements.png](images/guidelines/logo-elements.png)
- Logo Variants: [logo-variants.png](images/guidelines/logo-variants.png)
- Logo Colourways: [logo-colourways.png](images/guidelines/logo-colourways.png)
- Logo Nogos: [logo-nogos.png](images/guidelines/logo-nogos.png)
- Logo Clear Space: [logo-clear-space.png](images/guidelines/logo-clear-space.png)
- Logo Alignment: [logo-alignment.png](images/guidelines/logo-alignment.png)
- Color Palette Overview: [palette-overview.png](images/guidelines/palette-overview.png)
- Color Combinations Matrix: [colour-combinations.png](images/guidelines/colour-combinations.png)
- Typography (Parkinsans): [typography-parkinsans.png](images/guidelines/typography-parkinsans.png)
- Icons Style Guide: [icons-style-guide.png](images/guidelines/icons-style-guide.png)
- Charts & Diagrams: [charts-and-diagrams.png](images/guidelines/charts-and-diagrams.png)

---

## ⚡ Quick Start for Other Projects

```html
<!-- 1. Include Font -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Parkinsans:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<!-- 2. Include Brand Tokens -->
<link rel="stylesheet" href="path/to/brand-tokens.css">

<!-- 3. Use Brand Logo -->
<img src="path/to/images/logos/logo-wide-positive.svg" alt="Citizens' Track AI" height="40" />
```
