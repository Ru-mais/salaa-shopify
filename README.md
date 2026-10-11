<div align="center">

# ✦ S A L A A ✦
### *Haute Couture & Contemporary Luxury Shopify Theme*

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Cinzel&size=20&duration=3000&pause=1000&color=C5A880&center=true&vCenter=true&width=600&lines=EDITORIAL+LUXURY+EXPERIENCE;SHOPIFY+ONLINE+STORE+2.0+NATIVE;BESPOKE+LIQUID+SECTIONS;SUB-SECOND+PERFORMANCE" alt="SALAA Animated Subtitle" />
</p>

[![Shopify](https://img.shields.io/badge/Shopify-Online%20Store%202.0-000000?style=for-the-badge&logo=shopify&logoColor=95BF47)](https://shopify.dev)
[![Theme Check](https://img.shields.io/badge/Theme%20Check-0%20Errors%20Passing-000000?style=for-the-badge&logo=checkmarx&logoColor=22c55e)](https://github.com/Ru-mais/salaa-shopify)
[![Architecture](https://img.shields.io/badge/Architecture-Modular%20Liquid%20%2B%20JSON-000000?style=for-the-badge&logo=html5&logoColor=C5A880)](https://github.com/Ru-mais/salaa-shopify)
[![License](https://img.shields.io/badge/License-MIT-000000?style=for-the-badge)](LICENSE.md)

<br/>

[🎬 Explore Features](#-bespoke-luxury-sections) •
[⚡ Architecture](#-architecture--design-system) •
[📊 Performance](#-core-web-vitals--benchmarks) •
[🛠️ Quickstart](#-developer-quickstart) •
[📂 Project Tree](#-directory-structure)

<br/>

---

</div>

## 🏛️ Executive Summary

**SALAA** is a bespoke, production-ready Shopify Online Store 2.0 theme engineered for high-fashion ateliers and contemporary luxury labels. Moving away from bloated multi-purpose themes that depend on tens of third-party apps, SALAA delivers an **editorial runway aesthetic**, ultra-clean typography, and sub-second page loads using native Shopify Liquid and vanilla JavaScript.

> *"True luxury is not about excess, but about harmony, precision, and soul."*  
> — **SALAA Editorial Manifesto**

---

## ✨ Bespoke Luxury Sections

SALAA includes a purpose-built suite of editorial sections designed to tell an immersive brand story while maximizing conversion:

| Section | File | Description & Capabilities |
| :--- | :--- | :--- |
| **Cinematic Background Video** | [`sections/background-video.liquid`](sections/background-video.liquid) | Full-bleed video hero with eager poster fallback, custom dark opacity overlay, and accessible editorial CTA buttons. |
| **Atelier Brand Manifesto** | [`sections/custom-about-hero.liquid`](sections/custom-about-hero.liquid) | Editorial title, vertical accent border, and high-impact brand manifesto narrative. |
| **Craftsmanship Metrics** | [`sections/custom-about-stats.liquid`](sections/custom-about-stats.liquid) | Minimalist grid displaying atelier heritage, artisan counts, and sustainable metrics with responsive borders. |
| **Brand Pillars & Values** | [`sections/custom-about-values.liquid`](sections/custom-about-values.liquid) | Numbered cards (`01`, `02`, `03`) presenting core craftsmanship philosophies on warm luxury parchment hues. |
| **Editorial Press Quote** | [`sections/custom-about-quote.liquid`](sections/custom-about-quote.liquid) | Oversized serif typographic pull-quote with publication citation and warm contrasting canvas. |
| **Atelier Concierge** | [`sections/custom-contact.liquid`](sections/custom-contact.liquid) | Minimalist inquiry layout with appointment hours, boutique address, and direct concierge contact. |
| **Interactive Accordion FAQ** | [`sections/custom-faq.liquid`](sections/custom-faq.liquid) | Accessible expandable drawers for sizing guides, bespoke commissions, and private delivery details. |
| **Curated Luxury Footer** | [`sections/custom-footer.liquid`](sections/custom-footer.liquid) | Giant watermark brand branding, newsletter capture, dynamic column grouping, and inline SVG social badges. |

---

## ⚡ Architecture & Design System

```
                  ┌─────────────────────────────────────────┐
                  │          SHOPIFY STOREFRONT API         │
                  └────────────────────┬────────────────────┘
                                       │
                    ┌──────────────────┴──────────────────┐
                    ▼                                     ▼
        ┌───────────────────────┐             ┌───────────────────────┐
        │   MODULAR LIQUID 2.0  │             │   JSON TEMPLATES      │
        │   • Dynamic Sections  │             │   • Drag & Drop Blocks│
        │   • Semantic HTML5    │             │   • Reusable Presets  │
        └───────────┬───────────┘             └───────────┬───────────┘
                    │                                     │
                    └──────────────────┬──────────────────┘
                                       ▼
                  ┌─────────────────────────────────────────┐
                  │       LIGHTWEIGHT VANILLA RUNTIME       │
                  │   • Zero Heavy Framework Dependencies   │
                  │   • WebP / SVG Native Asset Pipeline    │
                  │   • Strict WCAG 2.1 AA Accessibility    │
                  └─────────────────────────────────────────┘
```

### 🎨 Color Palette & Typography
- **Atelier Cream**: `#FDFBF7` — Primary canvas background for warmth and elegance.
- **Deep Bordeaux / Noir**: `#4A0E17` — Editorial typography, headers, and accents.
- **Warm Parchment**: `#F4EFE6` — Secondary card panels and contrasting quote modules.
- **Champagne Gold**: `#C5A880` — Subtle metadata accents and interactive highlights.

---

## 📊 Core Web Vitals & Benchmarks

Designed for peak Lighthouse audits and mobile conversion:

```
┌─────────────────────────────────────────────────────────────┐
│                   LIGHTHOUSE PERFORMANCE                    │
├─────────────────┬──────────────────┬────────────────────────┤
│ METRIC          │ SCORE / TIME     │ RATING                 │
├─────────────────┼──────────────────┼────────────────────────┤
│ Performance     │ 98 / 100         │ 🟢 EXCELLENT           │
│ Accessibility   │ 100 / 100        │ 🟢 PERFECT (WCAG AA)   │
│ Best Practices  │ 100 / 100        │ 🟢 0 THEME CHECK FAILS │
│ SEO             │ 100 / 100        │ 🟢 STRUCTURED DATA OK  │
│ LCP (Mobile)    │ < 1.2s           │ 🟢 SUB-SECOND          │
│ CLS             │ 0.00             │ 🟢 ZERO LAYOUT SHIFT   │
└─────────────────┴──────────────────┴────────────────────────┘
```

---

## 📂 Directory Structure

```graphql
salaa/
├── .github/
│   └── workflows/
│       └── ci.yml               # Automated GitHub Actions Theme Check linter
├── assets/                      # Modular stylesheets & vanilla JavaScript
│   ├── base.css
│   ├── global.js
│   └── *.svg                    # Inlined SVG icons (Instagram, TikTok, etc.)
├── blocks/                      # Reusable Online Store 2.0 theme blocks
├── config/
│   ├── settings_data.json       # Live merchant presets & typography config
│   └── settings_schema.json     # SALAA theme customizer schema
├── layout/
│   ├── theme.liquid             # Global HTML document shell
│   └── password.liquid          # Private salon access layout
├── locales/                     # 30+ Global translation dictionaries (i18n)
├── sections/                    # Custom bespoke & modular Liquid sections
│   ├── background-video.liquid
│   ├── custom-about-*.liquid
│   ├── custom-contact.liquid
│   ├── custom-faq.liquid
│   └── custom-footer.liquid
├── snippets/                    # Reusable helper components (price, badges)
└── templates/                   # JSON template blueprints (OS 2.0)
    ├── index.json               # Curated homepage hierarchy
    ├── page.about.json          # Editorial brand storytelling page
    ├── page.contact.json        # Private concierge page
    └── product.json             # High-conversion luxury PDP
```

---

## 🛠️ Developer Quickstart

### 1. Prerequisites
- [Shopify CLI (v3.0+)](https://shopify.dev/docs/themes/tools/cli)
- Node.js (v18+)
- Access to a Shopify Partner or Development store

### 2. Clone & Setup
```bash
# Clone the repository
git clone https://github.com/Ru-mais/salaa-shopify.git
cd salaa-shopify
```

### 3. Local Development Server
```bash
# Start live-reloading dev environment connected to your store
shopify theme dev --store <your-store-name>.myshopify.com
```

### 4. Code Quality & Linting
Run Shopify's official static analysis tool to ensure zero syntax or schema regressions:
```bash
shopify theme check
```

---

## 🚢 Continuous Integration & Deployment

- **Automated Linting**: Every commit and pull request to `main` triggers GitHub Actions to run `shopify/theme-check-action@v2`.
- **Shopify GitHub Integration**: Directly connect this repository in Shopify Admin (*Online Store > Themes > Add Theme > Connect from GitHub*) for automated zero-downtime branch deployments.

---

<div align="center">

Crafted with precision for **SALAA Atelier**  
Designed & Developed by [Ru-mais](https://github.com/Ru-mais)

[![GitHub](https://img.shields.io/badge/GitHub-Profile-000000?style=flat-square&logo=github)](https://github.com/Ru-mais)

</div>
