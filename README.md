# Standard-Launch-Demo

This demo includes a single `index.html` page. The markup expects a handful of JPG and PNG files to live in an `assets/` directory:

- `assets/apple-touch-icon.png` – iOS home screen icon (`<link rel="apple-touch-icon">`).
- `assets/favicon-32.png` and `assets/favicon-16.png` – PNG favicons referenced in `<link rel="icon">` tags.
- `assets/favicon.ico` – fallback favicon for older browsers.
- `assets/logo.png` – used in structured data and other image references.
- `assets/logo.svg` – used as the mask icon and for the logo image in the navigation bar.
- `assets/og-image.jpg` – preview image for Open Graph metadata.
- `assets/hero-bg.jpg` – hero section background image.
- `assets/copper.jpg` – copper & brass card image.
- `assets/aluminum.jpg` – aluminum card image.
- `assets/steel.jpg` – steel & iron card image.
- `assets/stainless.jpg` – stainless steel card image.
- `assets/catalytic.jpg` – catalytic converters card image.
- `assets/batteries.jpg` – e‑scrap & batteries card image.

The HTML also links to a number of external resources:

- Google Fonts and Font Awesome are loaded via CDN links.
- A Google Maps iframe is embedded and requires a valid API key.

Image files are not tracked in version control. Before you deploy or customize the site, populate `assets/` with your own images matching the file names above.
The repository's `.gitignore` ignores common image extensions so you can keep your assets locally without committing them.
