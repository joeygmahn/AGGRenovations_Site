# AGG Renovations Website

Responsive single-page marketing site for AGG Renovations — bespoke renovation
services across kitchens, bathrooms and wet rooms, roofing, tiling, joinery,
flooring and intricate woodwork.

## Files

- `index.html` — full landing page: hero, services, about, projects slideshow, contact
- `styles.css` — responsive styling (brand colours set as CSS variables in `:root`)
- `images/` — `logo/` brand banner + `Portfolio/` project photos

## Sections

`#services` · `#about` · `#projects` (auto-playing slideshow) · `#contact`

## Contact form

No backend. On submit, JavaScript opens the visitor's email app pre-filled to
`enquiries@aggrenovations.co.uk`. If you later want submissions to land in an
inbox automatically, swap the JS handler for a form service (e.g. Formspree).

## Preview

Open `index.html` in a browser, or run a local static server:

```bash
python3 -m http.server
```

## Publishing

Static site — host anywhere. For GitHub Pages: push to a repo, enable Pages on
the default branch (root). Update the `og:url`/`canonical` URLs in `index.html`
to the live domain before going live.
