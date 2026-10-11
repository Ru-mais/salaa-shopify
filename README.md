# SALAA — Luxury Fashion Theme for Shopify

A modern, high-performance Shopify Online Store 2.0 theme crafted for contemporary luxury and high-fashion retail. Built with clean architecture, editorial aesthetics, bespoke storytelling sections, and responsive layouts.

---

## ✨ Features & Architecture

- **Online Store 2.0 Compliant**: Full JSON-based template support (`templates/*.json`) enabling dynamic section management and drag-and-drop hierarchy.
- **Bespoke Luxury Storytelling Sections**:
  - `background-video.liquid`: Immersive full-bleed hero video section.
  - `custom-about-hero.liquid`: High-impact brand manifesto header.
  - `custom-about-quote.liquid`: Editorial typographic quotes and brand philosophies.
  - `custom-about-stats.liquid`: Minimalist metric counters for craftsmanship and heritage.
  - `custom-about-values.liquid`: Grid-based values and brand pillar highlights.
  - `custom-faq.liquid`: Interactive accordion for sizing, bespoke orders, and shipping.
  - `custom-contact.liquid`: Minimalist inquiry and concierge contact section.
  - `custom-footer.liquid`: Luxury layout with newsletter capture and curated navigation.
- **Ultra-Lean Performance**: Zero external heavy framework bloat. Native Liquid, vanilla modern JavaScript, and optimized CSS.

---

## 📂 Project Structure

```
├── assets/         # Compiled stylesheets, vanilla JavaScript, and lightweight icons
├── blocks/         # Reusable theme app & section blocks
├── config/         # Theme settings schema and design presets (settings_data.json)
├── layout/         # Base HTML layout skeletons (theme.liquid, password.liquid)
├── locales/        # Internationalization & translation dictionaries
├── sections/       # Modular liquid sections & custom luxury components
├── snippets/       # Reusable Liquid snippets & utility helpers
└── templates/      # JSON template definitions for pages, products, and collections
```

---

## 🚀 Local Development

### Prerequisites
- [Shopify CLI 3.x+](https://shopify.dev/docs/themes/tools/cli)
- Active Shopify Partner or Development Store

### Running the Theme Dev Server

```bash
# Clone the repository
git clone https://github.com/Ru-mais/salaa-shopify.git
cd salaa

# Start the Shopify development preview server
shopify theme dev --store <your-dev-store>.myshopify.com
```

### Checking Theme Code
```bash
shopify theme check
```

---

## 📄 License
MIT License.
