# Tintabudi Design System
**Brand Design System v1.0 — Confidential**

Live reference: [tintabudi-design-system](https://yourusername.github.io/tintabudi-design-system/)

---

## Overview

This repository is the single source of truth for Tintabudi's visual identity. It contains all brand assets, typefaces, colour tokens, and usage guidelines for use across digital and print applications.

Tintabudi is a Kuala Lumpur-based bookstore and cultural brand. The design system reflects its core identity: ink, wisdom, and the written word.

---

## What's Inside

| Path | Contents |
|------|----------|
| `index.html` | Full interactive design system document |
| `assets/logo/` | Logo artwork in SVG and AI formats |
| `assets/fonts/` | Brand typeface (Winsel NorThi) |
| `assets/references/` | Brand direction PDFs and print guides |

---

## Logo Files

| File | Format | Use Case |
|------|--------|----------|
| `Tintabudi_LogoArtwork_Color_.svg` | SVG | Web, UI, all digital use |
| `Tintabudi_LogoArtwork_Color_.ai` | AI | Full colour print and editing |
| `Tintabudi_LogoArtwork.ai` | AI | Base logo artwork |
| `Tintabudi_LogoMark.ai` | AI | Mark/symbol only |
| `Tintabudi_Logotype.ai` | AI | Wordmark only |
| `TINTABUDI_Stamp_PRINT_W36xH36mm.ai` | AI | 36×36mm stamp variant for print |

> `.ai` files require Adobe Illustrator. For all digital and developer use, refer to the `.svg` file.

**Direct SVG URL (for use in code):**
```
https://raw.githubusercontent.com/yourusername/tintabudi-design-system/main/assets/logo/Tintabudi_LogoArtwork_Color_.svg
```

---

## Typography

**Brand Typeface:** Winsel NorThi  
**File:** `assets/fonts/Winsel-NorThi.otf`  
**Format:** OpenType (.otf)

To use in a web project:

```css
@font-face {
  font-family: 'Winsel';
  src: url('assets/fonts/Winsel-NorThi.otf') format('opentype');
  font-weight: 100;
  font-style: normal;
}
```

---

## Colour Tokens

| Name | Hex | Usage |
|------|-----|-------|
| Tintabudi Orange | `#F5AC48` | Primary brand colour, CTAs, highlights |
| Tintabudi Black | `#231F20` | Primary text, dark backgrounds |
| Mid Grey | `#B1B3B6` | Secondary text, borders, captions |
| Paper White | `#F7F5F0` | Page backgrounds, light surfaces |

---

## Reference Documents

Located in `assets/references/`:

- **Tintabudi_BrandDirection.pdf** — Brand strategy, tone of voice, and design philosophy
- **TIntabudi_ColorPalette.pdf** — Colour system and approved combinations
- **TIntabudi_Typography.pdf** — Type scale, hierarchy, and usage rules
- **Tintabudi_StoreFront_DecalDesign_Guide_.pdf** — Physical signage and decal specifications
- **TIntabudi_Poster_FinalArtwork_Square_.jpg** — Approved poster artwork reference

---

## Usage Guidelines

- Always maintain the logo clearspace (equal to cap height on all sides)
- Minimum digital logo size: 20px
- Do not recolour, distort, or apply effects to the logomark
- Approved colour combinations are documented in `index.html` under the Colour section

---

## For Developers

Clone the repo and open `index.html` locally to browse the full design system:

```bash
git clone https://github.com/yourusername/tintabudi-design-system.git
cd tintabudi-design-system
open index.html
```

No build step or dependencies required.

---

## Versioning

| Version | Date | Notes |
|---------|------|-------|
| v1.0 | March 2026 | Initial release |

---

## Contact

For brand or asset queries, contact the Tintabudi creative team.  
**Creative Direction:** Abdul Nazir  
**Website:** [tintabudi.com](https://tintabudi.com)

---

*This design system is confidential and intended for internal and approved partner use only.*
