# carlosalmonte.com

## What This Is

Carlos Almonte's personal site — personal brand, thought leadership, and portfolio. Content spans faith, family, music, business strategy, and life philosophy. The throughline: Innovation, Improvisation, Invention.

## Pages

- `index.html` — Homepage: hero, three pillars (Faith, Family, Work), featured article, events
- `about.html` — Full biography and background
- `writing.html` — Blog listing, filterable by category
- `work.html` — Portfolio and case studies
- `article.html` — Article detail template
- `admin.html` — CMS interface for managing articles without editing files directly

## Content

- Articles stored in `articles.json`
- Author metadata in `authors.json`
- Categories: faith, family, life, music, strategy, vocation
- Images in `/images/`

## Stack

- Vanilla HTML, CSS, JavaScript — no framework, no build step
- Google Fonts: Cormorant Garamond (serif), Outfit (sans-serif)
- Google Analytics via gtag.js
- Deployed to GitHub Pages, domain: carlosalmonte.com
- Git push to main = live

## Design Tokens

- `--ink: #1e2128`
- `--warm: #e8eaed`
- `--paper: #f4f5f7`
- `--gold: #c4745a`
- `--accent: #2c4a3e`
- Grain texture overlay throughout

## Conventions

- All styles are embedded per page — no external stylesheet
- No dependencies, no package.json
- Content updates go through `admin.html` which commits to git automatically
- Keep pages self-contained and fast-loading
