# Pratik & Rashmi Wedding Hub

Static, mobile-first wedding website for 24–25 November 2026 at Shakti Pathikasharm (Yevla Wala), Ambaji.

## Run locally

From this directory:

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173`.

## Configure before publishing

Edit `app.js`:

- Set `CONFIG.rsvpUrl` to the Google Form, WhatsApp link, or other RSVP destination.
- Replace the RSVP placeholder button behavior if a form is ready.
- Add family contact and gallery links in `index.html`.

## Publish on GitHub Pages

Create a GitHub repository, copy the contents of this folder into it, push to the default branch, then enable **Settings → Pages → GitHub Actions**. The included workflow deploys the site automatically on every push.

The site is buildless: GitHub Pages serves `index.html`, `styles.css`, `app.js`, and the assets directly.
