# Pratik & Rashmi Wedding Hub

Static, mobile-first wedding website for 24–25 November 2026 at Shakti Pathika Ashram, Ambaji.

## Run locally

From this directory:

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173`.

## Included

- English, Hindi, and Gujarati language switching
- Full two-day ceremony schedule
- Countdown and calendar download
- Google Maps directions, QR code, and family contact
- Four-page invitation booklets in all three languages

## Publish on GitHub Pages

Create a GitHub repository, copy the contents of this folder into it, push to the default branch, then enable **Settings → Pages → GitHub Actions**. The included workflow deploys the site automatically on every push.

The site is buildless: GitHub Pages serves `index.html`, `styles.css`, `app.js`, and the assets directly.
