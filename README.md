# BA Services US | Website

One-page, trilingual (EN / ES / FR) website for BA Services US, an accounting and business support firm.

## Structure
- `index.html` is the whole site: HTML, CSS and JS in one file, no build step.
- `assets/` holds the cream (dark backgrounds) and navy (light backgrounds) horizontal logos. The cream logo is also embedded in the page.

## Run locally
Open `index.html` in a browser. Fonts load from Google Fonts, so an internet connection is needed for the correct typography.

## Edit content
All text lives in the `TRANSLATIONS` object in the script, one block per language (`en`, `es`, `fr`). Each key matches a `data-i` attribute in the HTML.

## Deploy (GitHub Pages)
Settings > Pages > Deploy from a branch > `main` / root.

## Pending
- Booking tool for the 30-minute intro call (Google Calendar or Zoho).
- Contact form currently opens the visitor's email app; connect a form service if messages should be received directly.
- Native review of the French copy.
- Confirm domain admin and whether the address should be shown.
