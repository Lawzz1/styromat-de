# STYROMAT.DE — German-Market Website

Multi-page website for **Styromat**, a Polish manufacturer of clinker facade insulation panels
entering the German market. Real client project, currently in development.

🔗 **Live:** https://lawzz1.github.io/styromat-de/

## What's inside
- Multi-page site in German: product, color variants, components, legal pages (Impressum, Datenschutz)
- Before/after slider for facade renovations
- GSAP scroll animations
- DSGVO-compliant cookie banner
- Custom design system: brand blue `#3666D1`, Open Sans + Exo 2 (self-hosted fonts)
- Shared HTML templates for consistent header/footer across pages
- Dockerfile + deploy config for container hosting; GitHub Pages for the public preview

## How it was built
The site was produced with an AI-assisted agentic workflow (Claude API):
separate agent roles for research, design and frontend, with me reviewing and integrating the output.

## Structure
- `css/`: styles and design tokens
- `fonts/`: self-hosted web fonts
- `templates/`: shared page partials
- `deploy/`: deployment config
- `*.html`: pages
- `Dockerfile`: container build

## Related work for the same client
- AI video localization & TikTok publishing pipeline (Python): private, sanitized version in progress
- Live content: https://www.tiktok.com/@styromat.de

## Status
Work in progress. Content and pages are still being extended and documented.

---
Built by [Lev Horbatenko](https://github.com/Lawzz1) · Berlin
