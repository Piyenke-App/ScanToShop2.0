# ScanToShop 2.0

Barcode scanner and price comparison app for the Pi Network.

## What's included

- `index.html` — main app with Pi SDK, barcode scanning, and price lookup
- `privacy.html` — Privacy Policy (required for Pi App Studio)
- `terms.html` — Terms of Service (required for Pi App Studio)

## Pi SDK integration

The Pi SDK script is loaded in `index.html`:

```html
<script src="https://sdk.minepi.com/pi-sdk.js"></script>
```

**Before publishing to Pi Mainnet**, change `sandbox: true` to `sandbox: false` in `index.html`.

## Deploy to GitHub Pages

This repo is set up for GitHub Pages. After pushing to GitHub:

1. Open your repo on GitHub → **Settings** → **Pages**
2. Under **Build and deployment**, set **Source** to **GitHub Actions**
3. Push to `main` — the workflow deploys automatically

Your live URLs will be:

```
https://YOUR-GITHUB-USERNAME.github.io/scantoshop/
https://YOUR-GITHUB-USERNAME.github.io/scantoshop/privacy.html
https://YOUR-GITHUB-USERNAME.github.io/scantoshop/terms.html
```

## Pi App Studio — required URLs

| Field | URL |
|-------|-----|
| **App URL** | `https://YOUR-GITHUB-USERNAME.github.io/scantoshop/` |
| **Privacy Policy URL** | `https://YOUR-GITHUB-USERNAME.github.io/scantoshop/privacy.html` |
| **Terms of Service URL** | `https://YOUR-GITHUB-USERNAME.github.io/scantoshop/terms.html` |

## Test barcodes

- `3017620422003` — Nutella (has demo prices)
- `0737628064502` — sample barcode with demo prices
