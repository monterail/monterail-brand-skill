---
name: monterail-brand
description: "Apply Monterail's corporate visual identity to any artifact — HTML, React, PPTX, DOCX, dashboards, reports, landing pages. ALWAYS use when: user mentions 'Monterail', 'monterail style', 'our brand', 'firma style', 'firmowy styl', 'styl monterail', or when creating any Monterail-branded material (internal tools, client materials, demos, prototypes). Defines the complete design system: official colors (#F50031 red, #181016 dark), typography (Poppins + Inter), spacing, component patterns, real logo CDN URL, brand voice, and company facts. CRITICAL: Company name is always 'Monterail' (capital M) in all text — never lowercase except inside the logo graphic itself. Always use the official PNG logo from the CDN, never improvise it in SVG."
---

# Monterail Brand Skill

Apply Monterail's visual identity and brand voice consistently across all generated artifacts.

## ⚠️ Non-Negotiable Writing Rules

These apply to EVERY artifact, document, or text string you generate:

1. **Capitalization:** Always write **Monterail** (capital M). Never write `monterail`, `MONTERAIL`, or `monterrail`. The lowercase `monterail` form exists *only* inside the official logo wordmark graphic — it is never used in prose, code comments, filenames, slide text, or any other context.
2. **Logo source:** Always use the official PNG from the CDN URL below — never approximate the logo in SVG or draw it from scratch.
3. **Colors:** Use exact hex codes from this skill — never approximate or substitute brand colors.

## Design System Overview

Monterail's brand is modern, geometric, and confident. It uses bold red accents against dark backgrounds, clean sans-serif typography, and geometric patterns as decorative elements. The overall feel is professional tech company — not corporate-stuffy, but polished and intentional. The design philosophy emphasizes **sophisticated restraint** — minimalist, never overdesigned, with generous whitespace.

## Color Palette

Use these exact hex values. Do not approximate or substitute.

### Primary Brand Colors (from official Księga Znaku)

| Name | Hex | RGB | Role |
|------|-----|-----|------|
| **Monterail Red** | `#F50031` | R245 G0 B49 | **Official brand red** — logo sygnet, primary accent, CTAs, highlights |
| **Monterail Black** | `#181016` | R24 G16 B22 | Primary dark background, text on light backgrounds, logo wordmark |
| **White** | `#FFFFFF` | R255 G255 B255 | Text on dark, primary light background |

> **CRITICAL:** The official brand red is `#F50031` (Pantone 485C). The dark color is `#181016` (Pantone Black 3CP). These come directly from the Księga Znaku (brand book) and must be used for the logo and primary accents.

### Extended Palette (for UI, charts, secondary elements)

| Name | Hex | Role |
|------|-----|------|
| **Red Dark** | `#330818` | Dark accent backgrounds, hover states on red buttons |
| **Purple Dark** | `#2B1D5C` | Secondary dark background, section accents |
| **Purple** | `#6D58B4` | Secondary accent, tags, badges |
| **Green** | `#51C1B2` | Success states, secondary highlights, data viz accent |
| **Grey Dark** | `#939BA0` | Muted text, captions, secondary labels |
| **Grey** | `#DDE3E7` | Borders, dividers, subtle backgrounds |
| **Grey Light** | `#EDF0F2` | Light backgrounds, cards on white |

### Color Usage Rules

- **Primary background choices:** Dark (`#181016`) for hero/header sections, White/Grey Light for content sections.
- **Red (`#F50031`) is the signature color** — use it for primary buttons, active states, key highlights, and the Monterail logo. Never use it for large background fills (it's an accent, not a surface). The only exception is the social media avatar which uses Red as a circular background behind the white sygnet.
- **Purple Dark (`#2B1D5C`)** works well as an alternative dark section background to add variety.
- **Green (`#51C1B2`)** is for positive/success indicators and as a contrasting data visualization color.
- **Text colors:** White on dark backgrounds, Dark (`#181016`) on light backgrounds, Grey Dark (`#939BA0`) for secondary/muted text.
- Maintain strong contrast ratios — avoid Grey Dark text on Grey backgrounds.
- **Dark backgrounds are the primary mode** for Monterail — the website, presentations, and key materials favor light-on-dark designs.

## Typography

### Logo Typeface

The Monterail logotype wordmark is built on the **Dr** typeface by productiontype.com. The brand name is always written in **lowercase**: `monterail`. This typeface is used exclusively for the logo — do not use it for general content.

### Content Typography

Monterail uses **Poppins** for headings and **Inter** for body text in all digital materials.

### Font Loading (HTML/React artifacts)

Always import both fonts from Google Fonts at the top of any HTML or React artifact:

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
```

### Type Scale

| Element | Font | Weight | Size | Notes |
|---------|------|--------|------|-------|
| H1 | Poppins | 700 (Bold) | 44px / 2.75rem | Page/slide titles |
| H2 | Poppins | 600 (SemiBold) | 32px / 2rem | Section headers |
| H3 | Poppins | 600 | 24px / 1.5rem | Subsection headers |
| H4 | Poppins | 500 (Medium) | 18px / 1.125rem | Card titles, labels |
| H5 | Poppins | 500 | 14px / 0.875rem | Small headers, tags |
| Body | Inter | 400 (Regular) | 16px / 1rem | Default paragraph text (12pt in slides) |
| Body Small | Inter | 400 | 14px / 0.875rem | Secondary body text |
| Caption | Inter | 400 | 10px / 0.625rem | Footnotes, captions — UPPERCASE |

### Typography Rules

- Headings: `font-family: 'Poppins', sans-serif;`
- Body: `font-family: 'Inter', sans-serif;`
- Captions are always uppercase with letter-spacing `0.05em`
- Line height: 1.5 for body, 1.2 for headings
- Never use serif fonts or monospace fonts for UI text
- The brand name is always "monterail" (lowercase) when using the logotype, but "Monterail" (capitalized) in running text

## Layout & Spacing

### Spacing Scale

Use an 8px base grid:

| Token | Value | Use |
|-------|-------|-----|
| `xs` | 4px | Tight internal padding |
| `sm` | 8px | Between related elements |
| `md` | 16px | Standard padding |
| `lg` | 24px | Section internal padding |
| `xl` | 32px | Between sections |
| `2xl` | 48px | Major section breaks |
| `3xl` | 64px | Page-level margins |

### Layout Principles

- Use generous whitespace — Monterail's style breathes, it's not cramped
- Content max-width: 1200px for web artifacts, centered
- Card border-radius: 8px (consistent, not too round)
- Subtle shadows for elevation: `0 2px 8px rgba(24, 16, 22, 0.08)`
- No heavy borders — use Grey (`#DDE3E7`) 1px borders sparingly, prefer whitespace
- Photography style: professional, real people (team/client photos), never generic stock

## Visual Motifs

### Geometric Patterns

Monterail uses bold geometric patterns as decorative accents — zigzag/mountain shapes and angular patterns. These appear as:

- Background decorative elements in corners or edges (not filling entire backgrounds)
- Section dividers or hero section accents
- Built from the Red (`#F50031`) color or as subtle Grey overlays

When implementing geometric accents in HTML/React:
- Use SVG or CSS for the patterns, not images
- Keep them as accent elements — they should complement content, not compete with it
- Position them in corners, edges, or as subtle background elements
- The zigzag/mountain motif is the most recognizable — triangular peaks in Red

### Logo Treatment

The Monterail logo consists of two parts:
1. **Sygnet** — a geometric shape: a downward-pointing pentagon/chevron with three diagonal parallel stripes cut through the upper-right quadrant, built on a precise construction grid (Księga Znaku page 9).
2. **Wordmark** — "monterail" in lowercase, using the **Dr** typeface by productiontype.com.

#### Official Logo Asset

Always use the official PNG logo. **Two options in order of preference:**

**Option 1 — Embedded base64 (works offline, always use this in artifacts):**


**Option 1 — Embedded base64 (works offline, always use this in artifacts):**

```html
<img
  src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAIAAAACACAYAAADDPmHLAAARG0lEqVR42..."
  alt="Monterail sygnet"
  height="40"
/>

<!-- Full logo lockup -->
<div style="display:flex;align-items:center;gap:10px;">
  <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAIAAAACACAYAAADDPmHLAAARG0lEqVR42..." alt="Monterail" height="32" style="display:block;" />
  <span style="font-family:'Inter',sans-serif;font-weight:600;font-size:18px;letter-spacing:-0.02em;color:#181016;">Monterail</span>
</div>
```

**Option 2 — CDN URL (use as fallback or when internet is guaranteed):**

```
https://a.storyblok.com/f/202591/566x570/d021a08896/monterail-logo-sygnet-red.png/m/1536x1536/filters:format(png):quality(100)
```
> **Note on the wordmark:** The "Dr Web" typeface is a commercial font. As a fallback in HTML, use `font-family: 'Inter', sans-serif; font-weight: 600; letter-spacing: -0.03em; text-transform: lowercase;` which approximates the style. For pixel-perfect branded output (PPTX, DOCX), reference only the sygnet PNG and type the wordmark in a provided/licensed font.

**Logo usage rules (from Księga Znaku):**
- The sygnet uses Red (`#F50031`) — never change its color except to White (negative/dark bg) or Black (`#181016`) for achromatic version
- The wordmark "monterail" appears next to the sygnet in **lowercase** — this is the only place lowercase is correct
- Wordmark color: White on dark backgrounds, Dark (`#181016`) on light backgrounds
- Position in top-left or top-center of layouts
- **Clear zone (pole ochronne):** minimum clear space around the logo equals the height of the "M" letter in the wordmark on all sides
- **Forbidden:** Never change proportions, rotate, distort, add effects, recolor the sygnet (only Red/White/Black allowed), or modify the wordmark font
- **Avatar format:** Red circle background (`#F50031`) with white sygnet centered inside (for social media profiles)

## Brand Voice & Messaging

### Tone of Voice

- **Professional, confident, welcoming** — not corporate-stiff, not startup-casual
- **Brand promise:** "Every great product starts with a conversation"
- **Brand personality:** Ambitious, Trustworthy, Innovative, Human-centered, Professional

### Messaging Architecture

1. **Primary:** "The New Default" — positioning as the standard in the industry
2. **Secondary:** Partnership and long-term relationships
3. **Tertiary:** Quality, expertise, proven track record

### Content Style Guide

**Do use:**
- Partnership-oriented language ("together", "our collaboration", "your partner")
- Value-driven messaging (results, impact, outcomes)
- Storytelling through case studies
- Direct, one-sentence CTAs
- Confident, clear statements

**Avoid:**
- Transactional language ("vendor", "provider", "supplier")
- Corporate clichés ("synergy", "leverage", "best-in-class")
- Overly salesy copy
- Generic tech buzzwords without substance
- Passive voice in CTAs

### Core Values (use in internal materials, careers pages, culture content)

1. **Keep the professional promise** — collaboration, technical expertise, transparent communication
2. **Get things done** — ownership, accountability, solutions over blame
3. **Evolve and adapt** — continuous learning, innovation balanced with best practices
4. **Embrace diversity** — inclusive culture, different perspectives drive innovation

## Company Facts (for content generation)

Use these verified facts when creating Monterail-branded materials:

| Fact | Value |
|------|-------|
| Founded | 2009 |
| Location | Wrocław, Poland (ul. Oławska 27-29) |
| Team size | 130+ experts |
| Projects completed | 900+ |
| NPS score | 71 |
| Co-CEOs | Szymon Boniecki & Bartosz Rega |
| Email | hello@monterail.com |
| Phone | +48 533 600 136 |
| Website | www.monterail.com |

### Key Partnerships & Credentials
- Official Vue.js Partner (since 2019)
- Official Nuxt Partner (since 2024)
- Recognized by Clutch, Financial Times 1000 (2018), Deloitte (2016)
- Acquired Untitled Kingdom (MedTech, 2024) and ElPassion (product design, 2025)

### Service Lines
- Web Development
- Mobile Development
- Product Design (UI/UX)

### Notable Clients
Bosch, Doctolib, EY, Merck, SharkNinja

## Component Patterns

### Buttons

```css
/* Primary */
.btn-primary {
  background: #F50031;
  color: #FFFFFF;
  font-family: 'Poppins', sans-serif;
  font-weight: 600;
  font-size: 14px;
  padding: 12px 24px;
  border-radius: 8px;
  border: none;
  cursor: pointer;
  transition: background 0.2s;
}
## Component Patterns

### Buttons

```css
.btn-primary:hover {
  background: #330818;
}

/* Secondary */
.btn-secondary {
  background: transparent;
  color: #F50031;
  border: 2px solid #F50031;
  font-family: 'Poppins', sans-serif;
  font-weight: 600;
  font-size: 14px;
  padding: 12px 24px;
  border-radius: 8px;
  cursor: pointer;
  transition: all 0.2s;
}
.btn-secondary:hover {
  background: #F50031;
  color: #FFFFFF;
}
```

### Cards

```css
.card {
  background: #FFFFFF;
  border-radius: 8px;
  padding: 24px;
  box-shadow: 0 2px 8px rgba(24, 16, 22, 0.08);
}
/* On dark backgrounds */
.card-dark {
  background: #2B1D5C;
  color: #FFFFFF;
}
```

### Navigation / Header

- Dark background (`#181016`)
- Logo left, nav items right
- Nav text in Inter 500, white, with Red underline/highlight on active
- Sticky positioning preferred

### Data Visualization Colors

When creating charts or graphs, use this ordered palette:
1. `#F50031` (Red)
2. `#6D58B4` (Purple)
3. `#51C1B2` (Green)
4. `#2B1D5C` (Purple Dark)
5. `#939BA0` (Grey Dark)

## Artifact-Specific Guidance

### HTML / React Artifacts

- Set `background: #FFFFFF` or `#EDF0F2` for the page body
- Use a dark (`#181016`) hero/header section with white text
- Import Poppins + Inter from Google Fonts
- **Always render the logo using the official CDN PNG** (see Logo Treatment section above)
- Apply the CSS variable pattern for easy theming:

```css
:root {
  --monterail-red: #F50031;
  --monterail-red-dark: #330818;
  --monterail-dark: #181016;
  --monterail-purple-dark: #2B1D5C;
  --monterail-purple: #6D58B4;
  --monterail-green: #51C1B2;
  --monterail-grey-dark: #939BA0;
  --monterail-grey: #DDE3E7;
  --monterail-grey-light: #EDF0F2;
  --monterail-white: #FFFFFF;
  --font-heading: 'Poppins', sans-serif;
  --font-body: 'Inter', sans-serif;
  /* Official logo CDN URL — use in <img src="..."> */
```

### Cards

```css
.card {
  background: #FFFFFF;
  border-radius: 8px;
  padding: 24px;
  box-shadow: 0 2px 8px rgba(24, 16, 22, 0.08);
}
/* On dark backgrounds */
.card-dark {
  background: #2B1D5C;
  color: #FFFFFF;
}
```

### Navigation / Header

- Dark background (`#181016`)
- Logo left, nav items right
- Nav text in Inter 500, white, with Red underline/highlight on active
- Sticky positioning preferred

### Data Visualization Colors

When creating charts or graphs, use this ordered palette:
1. `#F50031` (Red)
2. `#6D58B4` (Purple)
3. `#51C1B2` (Green)
4. `#2B1D5C` (Purple Dark)
5. `#939BA0` (Grey Dark)

## Artifact-Specific Guidance

### HTML / React Artifacts

- Set `background: #FFFFFF` or `#EDF0F2` for the page body
- Use a dark (`#181016`) hero/header section with white text
- Import Poppins + Inter from Google Fonts
- **Always render the logo using the official CDN PNG** (see Logo Treatment section above)
- Apply the CSS variable pattern for easy theming:

```css
:root {
  --monterail-grey-light: #EDF0F2;
  --monterail-white: #FFFFFF;
  --font-heading: 'Poppins', sans-serif;
  --font-body: 'Inter', sans-serif;
  /* Official logo CDN URL — use in <img src="..."> */
  --monterail-logo-url: url('https://a.storyblok.com/f/202591/566x570/d021a08896/monterail-logo-sygnet-red.png/m/1536x1536/filters:format(png):quality(100)');
}
```

**Standard header/nav pattern with real logo (use base64 src — works offline):**

```html
<header style="background:#181016;padding:16px 32px;display:flex;align-items:center;justify-content:space-between;">
  <div style="display:flex;align-items:center;gap:10px;">
    <img
      src="data:image/png;base64,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"
      alt="Monterail"
      height="32"
    />
    <span style="color:#fff;font-family:'Inter',sans-serif;font-weight:600;font-size:18px;letter-spacing:-0.02em;">Monterail</span>
  </div>
  <!-- nav items here -->
</header>
```

### Presentations (PPTX)

- Default slide background: White or Grey Light
- Title slides: Dark (`#181016`) background with white Poppins text
- Accent geometric shapes in Red in corners
- Section labels in uppercase Inter caption style
- Use Red (`#F50031`) for emphasis/highlight elements
- Include Monterail logo (sygnet or full) on title and closing slides
- Stats slides: use large Poppins Bold numbers in Red with Inter descriptions

### Documents (DOCX / PDF)

- Headings in Poppins Bold, body in Inter Regular
- Red (`#F50031`) accent for horizontal rules or highlight boxes
- Grey Light for callout/tip boxes
- Page numbers in Grey Dark, Inter caption style
- Cover pages: Dark (`#181016`) background with white text and Red accents
- Headers/footers: include Monterail logo, use Grey Dark for page info

### Markdown Artifacts

- Use the color values in any inline HTML styling
- Headers map to Poppins sizing: H1=44px, H2=32px, H3=24px

## Anti-Patterns (Avoid These)

- **NEVER write "monterail" in lowercase in any text, document, or code** — the lowercase form exists exclusively inside the official logo wordmark graphic. In prose, headings, slide text, alt attributes, filenames, code comments — it is always **Monterail** (capital M).
- Do NOT improvise the logo in SVG or draw it from scratch — always use the official CDN PNG URL
- Do NOT use blue as a primary color — Monterail's accent is Red (`#F50031`)
- Do NOT use `#ED0133` or other approximate reds — use the official `#F50031`
- Do NOT use rounded-full (pill) buttons — use 8px border-radius
- Do NOT use gradients — Monterail uses flat, solid colors
- Do NOT use serif fonts anywhere
- Do NOT use thin/light font weights for headings — Poppins headings are always 500+
- Do NOT put Red text on Dark backgrounds for body text (use White instead, Red only for accents/highlights)
- Do NOT use generic Tailwind blue/indigo defaults — override with Monterail palette
- Do NOT use generic stock imagery — prefer professional photos of real people
- Do NOT use overly colorful, chaotic designs — Monterail is restrained and minimalist
- Do NOT use transactional/vendor language — always frame as partnership
- Do NOT modify logo proportions, add elements to the logo, or use non-approved colors for the sygnet

