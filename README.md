# Syncomics AI LLC — Landing Page

A modern, responsive, single-page website built with semantic HTML and accessible CSS.

## Quick start

Open `index.html` in your browser. No build step required.

## Structure

- `index.html` — All content sections (Hero, About, Expertise, Services, Collaboration, Why Syncomics, CTA, Footer)
- `styles.css` — Global styles, layout, cards, buttons, responsive rules
- `assets/brand-logo.png` — Your exact provided logo (used for header + hero + favicon). If missing, the site will temporarily fall back to `assets/logo.svg`.
- `assets/integration-insight.png` — The integration → unified insight figure shown under the hero. If missing, the site will temporarily fall back to `assets/service-integration.svg`.

Optional HTML-embedded logo
- You can also use your HTML embed file. Save it as `assets/brand-logo.html` (for example, the provided `syncomics_logo_embed.html`). The header and hero will auto-prefer this HTML embed and hide the PNG/SVG fallback once it loads.

Web-friendly formats
- If you have very large PNG/JPGs, consider adding a WebP alongside them for faster loads:
	- `assets/integration-insight.webp` (optional). The page will automatically use WebP when available and fall back to PNG.
- `assets/service-*.svg` — Lightweight science/tech illustrations for each service card

## Branding and accessibility

- Predominantly white; headings in dark purple, accents in navy and silver.
- High-contrast colors and large tap targets.
- Uses `prefers-reduced-motion` to respect user motion settings.
- Smooth scrolling to sections (disabled automatically for reduced-motion users).

## Contact

The site intentionally does not display the email address. The buttons "Start a Collaboration" and "Contact Us" use `mailto:` links and are the only ways to initiate email contact via the page.

## Using your provided logo

- If you have a PNG/JPG logo you prefer, place it at `assets/logo.png` and change the header image source in `index.html` from `assets/logo.svg` to `assets/logo.png`. The SVG provided matches the requested dark purple/navy/silver palette and remains crisp on all screens.
