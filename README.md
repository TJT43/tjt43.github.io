# Talha Jubaer — Applied Chemist Portfolio

A dark, minimal, animated single-page portfolio with a chemistry theme — molecular canvas background, periodic-table-style skill tiles, and SVG molecule accents. Deployed via GitHub Pages using "Deploy from a branch" (`main`).

🔗 **Live site:** [tjt43.github.io](https://tjt43.github.io)

## Sections

- **Hero** — name, tagline, animated intro with a floating molecule
- **About** — short bio + animated stat counters
- **Skills** — periodic-table-style element tiles
- **Projects** — project cards with molecular icons
- **Contact** — email, phone, location, and social links

## Tech

- Plain **HTML / CSS / JS** — no build step, no dependencies
- ~3 files: `index.html`, `styles.css`, `script.js`
- Responsive (mobile hamburger nav)
- `prefers-reduced-motion` aware
- Custom `<canvas>` particle network for the molecular background

## Customize

All content lives in `index.html` as plain text. Edit:

- **Name / titles** — search for `Talha Jubaer`
- **Bio** — `.about-text` section
- **Skills** — `.skill-tile` elements (symbol + name)
- **Projects** — `.project-card` elements
- **Contact details** — email, phone, LinkedIn in the `#contact` section
- **Colors** — CSS variables at the top of `styles.css` (`--accent`, `--bg`, etc.)

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

Deployed via GitHub Pages using the **Deploy from a branch** option.

---

Built with care · `C₈H₁₀N₄O₂` fueled by caffeine.
