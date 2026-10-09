# Ethiopian Super Intelligence Institute (SII) — sii.et

Rebuilt clone of [aii.et](https://aii.et) (Ethiopian Artificial Intelligence Institute) with full content capture and a complete modern redesign.

## Rebrand
- Artificial Intelligence → **Super Intelligence**
- AII / EAII → **SII / ESII**
- Domain: **sii.et** (previous: aii.et)
- Subdomains mapped: startup (`aistartup.sii.et`), summer-camp, news, patents, HR system, call-for-papers

## What's rebuilt
- **Index**: modern hero, cards, articles list, subdomain links
- **Articles (5)**: patents, HR launch, startup program, call for papers, summer camp
- **Pages (7)**: startup, summer-camp, news, patents, hr-system, call-for-papers, about
- **CSS**: dark mode (`#0b0c15` base), mobile-first hamburger nav, gradient text (`#c4a8ff` → `#6ee7ff`), glassmorphism nav, card grid
- **Logo**: new SVG with SII branding
- **GitHub repo**: [axialhash/sii-et](https://github.com/axialhash/sii-et)

## Original site issues fixed
- Glitchy SPA (React hydrate on nginx static) replaced with clean static HTML + minimal CSS/JS
- No mobile hamburger navigation added
- No dark mode → mandatory dark mode (next-themes style)
- No emoji (design bar enforced)
- Copy of globals.css style from harar.dev platform conventions

## Deployment
Ready for `sii.et`. Point DNS A/AAAA to host, upload `/home/hash/sii-et-build` contents, set root to `index.html`. All internal links relative (`/css/`, `/pages/`, `/articles/`).
