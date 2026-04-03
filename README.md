# FJELL™ — Modular Micro-Cabin System

**Norwegian Design. Global Reach. Build from Files.**

[![License](https://img.shields.io/badge/License-Proprietary-black)](mailto:pagalysm@gmail.com)
[![Version](https://img.shields.io/badge/Version-3.0-2d5a27)](https://github.com/Atarasfrux/FJELL_Website)
[![Files](https://img.shields.io/badge/DXF_+_STL-46_files-4a8c3f)](../README.md)

<div align="center">

## Build a cabin. From files.

Professional DXF & STL files for modular cabins under 15m². No building permit needed in Norway. Build in one weekend.

**[→ View Live Landing Page](https://mantzu132.github.io/FJELL_Website/)**

</div>

---

## What's This?

This repository hosts the **FJELL™ landing page** — a single-file, zero-dependency website for our modular micro-cabin system. The full file package (40 DXF + 6 STL files) lives in the parent [FJELL_Master](..) repository.

## Quick Start

The landing page is a single `index.html` file — no build step, no dependencies, no frameworks.

```bash
# Open locally
open index.html

# Or serve with any static server
python -m http.server 8000
```

## Deployment

### GitHub Pages (Recommended)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://<username>.github.io/FJELL_Website/`

### Alternative: Netlify

```bash
# Drag and drop the folder at app.netlify.com/drop
# Or use Netlify CLI:
netlify deploy --prod --dir=.
```

### Alternative: Vercel

```bash
vercel --prod
```

## File Structure

```
FJELL_Website/
├── index.html          ← Landing page (single file, ~800 lines)
└── README.md           ← This file
```

## Features

- **Zero dependencies** — no frameworks, no build tools, no CDN calls
- **Works offline** — all CSS and JS inlined
- **Responsive** — mobile-first, works on all devices
- **SEO optimized** — meta tags, Open Graph, semantic HTML
- **Fast** — single HTTP request, ~30KB total
- **Accessible** — proper contrast ratios, keyboard navigation

## Sections

| Section | Purpose |
|---------|---------|
| Hero | Value proposition + CTAs |
| Stats | Key numbers at a glance |
| Cabins | 4 package cards (LAND/CAMP/FORM/ROAM) |
| Pricing | 3 digital file tiers (Basic/Complete/Premium) |
| Coming Soon | Full material kits with corrected pricing |
| Comparison | vs. Norwegian competitors |
| Specs | Technical specifications table |
| FAQ | 8 common questions with accordion |
| CTA | Final conversion section |
| Footer | Contact info + links |

## Pricing Data (Integrated)

All pricing is based on verified cost analysis:

| Tier | NOK | EUR | USD |
|------|-----|-----|-----|
| **BASIC** | 2,500 | €250 | $250 |
| **COMPLETE** | 4,500 | €350 | $450 |
| **PREMIUM** | 10,000 | €800 | $1,000 |

Full kit pricing (coming Q2 2026) is based on dimension-based material cost analysis showing current market rates are 40-75% below competitors.

## Competitor Data Sources

- Norske Mikrohus: [Dwell Article](https://www.dwell.com/article/norske-mikrohus-prefab-tiny-houses-norway-c7de1c56) — $103K-$150K USD
- Modulbygg Veslemøy: [micro-living.no](https://micro-living.no/veslemoy/) — 527,000 NOK kit
- MCabin Line M24: [mcabinline.com](https://www.mcabinline.com/no/m24) — ~450,000+ NOK base kit

## Contact

| | |
|---|---|
| **Designer** | Mantas Pagalys |
| **Email** | pagalysm@gmail.com |
| **Phone** | +47 477 49 934 |
| **Location** | Tynset, Norway |
| **GitHub** | [@mantzu132](https://github.com/mantzu132) |

---

**FJELL™ — Norwegian Design · Norwegian Climate · Norwegian Quality**

*v3.0 · © 2026 FJELL Design · All rights reserved*
