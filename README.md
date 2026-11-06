# SD Pixel Studio — GitHub Pages package

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Extract this ZIP and upload the **contents** of this folder to the repository root. Keep `index.html` at the root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for GitHub Pages to publish; the site URL appears in Pages settings.

## Included
- `index.html` — main website entry page.
- `pages/` — alternate Stitch page exports.
- `previews/` — compressed WebP preview images.
- `stitch-pages.html` — responsive visual gallery.
- `404.html` — branded not-found page.
- `favicon.svg` — browser tab icon.
- `.nojekyll` — GitHub Pages marker.

## Optimization applied
- Converted preview screenshots from PNG to WebP.
- Added lazy loading and asynchronous decoding to gallery preview images.
- Added responsive gallery layout, metadata and a lightweight 404 page.
- Preserved original page HTML/CSS/JavaScript exports instead of aggressively minifying them, reducing the risk of breaking interactions.
- Checked local page links.

## Backend limitation
GitHub Pages is static hosting. The included admin screens are front-end designs, not a functioning secure admin system. Google sign-in, access control, database sync and persistent image uploads require a configured backend such as Firebase or another server. Never place private API keys or service-account credentials in this repository.

## Before publishing
Review contact details, WhatsApp numbers, email addresses, social links, prices, portfolio imagery and placeholder content. Some exported pages load fonts, Tailwind CSS or images from external services and therefore need an internet connection.
