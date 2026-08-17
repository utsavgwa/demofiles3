# Mandrake & Moonstone

A single-page concept site for a fictional wizarding apothecary house, built as a
static page with no build step, no dependencies, and no external requests.

<!-- **Live:** http://utsav23.com/demofiles3/ -->

## What this is

The page borrows the section architecture common to large corporate pharma
homepages — sticky header, hero banner, thesis line, feature card, story grid,
news grid, explore cards, newsletter banner, deep footer — and fills it with
entirely original wizarding-world copy. It is a fan-made concept and is not
affiliated with any real company or rights holder.

## Notes

- `index.html` is the whole site. No framework, no fonts fetched, no images
  requested — all artwork is inline SVG plus a canvas starfield.
- Light and dark themes are handled through CSS custom properties, covering all
  three viewer states: explicit light, explicit dark, and OS default.
- Built against WCAG 2.2 AA: skip link, landmark structure, focus-trapped mobile
  drawer, 24–44px target sizes, two-tone focus rings, `prefers-reduced-motion`
  support, and a polite live region for status messages.

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000
