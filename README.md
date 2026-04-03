# monterail-brand-skill

A Claude skill that applies [Monterail's](https://monterail.com) corporate visual identity consistently across all AI-generated artifacts — HTML pages, React components, presentations, documents, dashboards, and more.

## What it does

When active, the skill instructs Claude to:

- Use **exact brand colors** (`#F50031` red, `#181016` dark, full extended palette)
- Use **Basier Circle** as the official content typeface (via Fontshare CDN)
- Use the **correct SVG logo files** from `assets/` — never improvise or approximate
- Apply the **8px spacing grid**, card patterns, button styles, and navigation templates
- Follow **brand voice guidelines** — confident, partnership-oriented, no clichés
- Avoid all documented **anti-patterns** (wrong fonts, wrong reds, pill buttons, gradients, etc.)

## Preview

Open [`monterail-brand-skill-showcase.html`](./monterail-brand-skill-showcase.html) in a browser to see a full demonstration of what the skill enables — colors, typography, logo variants, components, brand voice, and anti-pattern examples.

## Installation

Install the `.skill` file in Claude's skill manager:

👉 [monterail-brand skill on Claude](https://claude.ai/customize/skills?selectedId=skill_01HHTnAMPULhKuJGRU7Nf1t9)

## Assets

All logo files are pixel-perfect SVGs derived from the official Księga Znaku (brand book):

| File | Description |
|------|-------------|
| `assets/logo-color.svg` | Full wordmark + sygnet — for light backgrounds |
| `assets/logo-white.svg` | Full wordmark + sygnet — for dark backgrounds |
| `assets/logo-black.svg` | Full logo in monochrome `#181016` |
| `assets/sygnet-color.svg` | Sygnet only in `#F50031` |
| `assets/sygnet-white.svg` | Sygnet only in `#FFFFFF` |
| `assets/sygnet-black.svg` | Sygnet only in `#181016` |
| `assets/avatar.svg` | Red circle + white sygnet — social media avatar |

## Changelog

### v2.0
- **Typography:** Replaced Poppins + Inter with **Basier Circle** (official brand typeface)
- **Logos:** Replaced CDN PNG with **pixel-perfect SVG files** in `assets/`
- **Color fix:** Grey Light corrected from `#EDF0F2` → `#F3F5F6`
- **Motif docs:** Added geometric decorative pattern documentation with CSS implementation
- **CSS variables:** Unified `--font-brand` replacing separate `--font-heading` / `--font-body`

### v1.0
- Initial skill — Poppins + Inter typography, CDN PNG logo, full color palette, brand voice, component patterns

## Maintainer

[@d0pawlus](https://github.com/d0pawlus) · Monterail
