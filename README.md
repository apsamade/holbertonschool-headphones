# Headphones - Landing Page

A fully responsive static HTML/CSS landing page for a headphones brand, built as a Holberton School project.

## Design

Designed by **Nicolas Philippot** (UI/UX designer). The implementation matches the Figma mockup at three responsive breakpoints:

- **Desktop** (> 768px) - Full layout with 4 items per row
- **Tablet** (481px - 768px) - 2x2 grid layout
- **Mobile** (< 480px) - Single column stacked layout with hamburger menu

## Sections

| Section | Description |
|---------|-------------|
| **Header / Hero** | Navigation bar, hero image with CTA button |
| **What we do** | 4 feature cards with custom Holberton icon font |
| **Our results** | Pentagon-shaped stats on dark background |
| **Contact us** | Minimal contact form with underline inputs |
| **Footer** | Logo, social links, copyright |

## Architecture

Progressive enhancement across 5 paired versions:

- `0-index.html` / `0-styles.css` - Header + Hero
- `1-index.html` / `1-styles.css` - + What We Do
- `2-index.html` / `2-styles.css` - + Our Results
- `3-index.html` / `3-styles.css` - + Contact Form
- `4-index.html` / `4-styles.css` - + Footer (final version)

## Constraints

- No external CSS frameworks (Bootstrap, Tailwind, etc.)
- No JavaScript
- Mobile-first hamburger menu using CSS checkbox hack
- Custom icon font (`holberton_school-icon`)
- Fonts: **Source Sans Pro** (body), **Spin-Cycle-OT** (decorative)

## Assets

- `/fonts/` - Source Sans Pro + Holberton icon font
- `/images/` - Hero images, logo, social icons, pentagon shape
- `/mes_ressources/` - Designer reference image
