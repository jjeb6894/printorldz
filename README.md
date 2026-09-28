# Printorldz

A lightweight, static, retro-2008-styled website for CNC/CAM enthusiasts. Pure
HTML and CSS &mdash; no JavaScript frameworks, no build tools, no dependencies.

## Pages

- `index.html` &mdash; Home page introducing Printorldz.
- `catalog.html` &mdash; A big informational reference table of well-known CNC
  machine brands/models and historical/legacy CAM &amp; CNC control software,
  each with a short description, era, and status (Active/Legacy/Discontinued).
  Purely informational: no license keys, no download links for paid software.
- `downloads.html` &mdash; A curated list of software that has genuinely become
  freeware, open-source, or offers a real free tier over time (e.g. TurboCNC,
  LinuxCNC, GRBL, KCam free edition, Mach3 demo, Fusion 360 personal use,
  FreeCAD, DraftSight's historical free edition). Every link points to the
  official vendor/project site &mdash; never a mirror or file host.
- `store.html` &mdash; A small demo shop of first-party Printorldz digital
  products (placeholder guides/cheat sheets) with decorative, non-functional
  "Add to Cart" buttons. No real payment processing, no license key
  marketplace, and no key checker/validator of any kind.
- `about.html` &mdash; About the site and how to get in touch.

## Design

Styled to look like an authentic circa-2008 hobbyist website: gradient
headers, beveled/outset buttons, a CSS-animated "marquee" welcome banner,
a fake hit-counter graphic, visible table borders, a right sidebar with
placeholder affiliate banners, and a "best viewed at 1024x768" footer note.
All shared styling lives in `style.css`; simple banner/hit-counter graphics
are hand-drawn SVGs in `images/`.

## Viewing the site

No build step is required. Either:

1. Open `index.html` directly in your browser, or
2. Serve it locally:

   ```sh
   python3 -m http.server
   ```

   then visit `http://localhost:8000/` in your browser.

## Scope / out of scope

This project intentionally does **not** include: license key generators,
key checkers/validators, multi-seller marketplace features, or download
links to cracked/paid software. The Downloads page links only to official
sources for software that is genuinely free/freeware/open-source, and the
Store sells only original, first-party Printorldz content.
