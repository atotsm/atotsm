# atotsm

**A Taste of the Social Media**

The central public gateway to an interconnected body of philosophical, intellectual, creative, technological and practical work.

## Project principles

- Static-first, lightweight and mobile-friendly.
- No mandatory framework or build system.
- Semantic HTML, custom CSS and minimal JavaScript.
- Independent publications connect to the central ecosystem.
- Shared identity, navigation and support infrastructure.

## Project structure

- `index.html` — central landing page.
- `assets/css/` — visual styles.
- `assets/js/` — interactive behaviour.
- `assets/images/` — visual assets.
- `docs/` — architecture and development notes.

## Local development

Run `python3 -m http.server 8000 --bind 127.0.0.1` from this directory.

Open `http://127.0.0.1:8000` in your browser.

## Version 3 update

V3 builds on the supplied V2 rather than replacing its narrative. It adds:

- A visual, navigable map connecting the four main modes of exploration.
- Social-sharing metadata and an explicit light colour-scheme declaration.
- Improved mobile-menu accessibility and visual open-state feedback.
- Responsive connection cards that remain usable on narrow screens.

No external destinations, contact details, payment links or publication links have been invented. The original V2 narrative is retained in `docs/v2-narrative.md`.

## Deployment

GitHub Pages or another static hosting provider. Hosting is not configured yet; connect the intended GitHub repository before publishing.
