# South County K9

Website for South County Canine Association — retired police K-9s, Chula Vista, CA.

## Files

- `South County Canine Association v2.dc.html` — Latest design (v2)
- `South County Canine Association.dc.html` — Original design (v1)
- `support.js` — DC runtime engine (React-based renderer)
- `image-slot.js` — Image slot component
- `uploads/` — Site images (avif format)

## Format

This is a `.dc.html` design canvas export. It renders via the bundled `support.js` React runtime. No build step required — open the HTML file directly in a browser.

## Deployment

To deploy as a static site, the v2 file can be served as `index.html` alongside `support.js`, `image-slot.js`, and the `uploads/` folder.
