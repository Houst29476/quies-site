# quies-site

Static marketing + legal site for Quies. Mirrors the [auris-site] pattern:
folder-per-page with `index.html`, no build step.

## Pages

- `/` — landing page
- `/privacy/` — privacy policy (linked from ASC App Information)
- `/support/` — support page (linked from ASC App Information)
- `/terms/` — terms of use

## Deploy

This folder is intended to be pushed to a separate GitHub repo
(suggested: `Houst29476/quies-site`) and served via GitHub Pages.

```bash
# From a new clone of the empty quies-site repo:
cp -r /Users/masdineroventures/mas-dinero-monorepo/quies-site/* .
git add .
git commit -m "Initial site"
git push
```

Once Pages is enabled on the repo, the site lives at:
- Temp: `https://houst29476.github.io/quies-site/`
- Production: `https://quies.app` once the domain is registered + configured

## Replace before any submission

- App Store listing URLs must match the live URLs of `/privacy/` and `/support/`
- CTA on landing page currently says "Coming soon to the App Store" — swap to
  a real App Store link the day the app goes live
- Email `support@quies.app` needs to forward somewhere real before submission
  (the policy + support pages both list it)

## Brand tokens used in CSS

- Midnight `#0A1628` — body background
- Ocean slate `#142339` — cards, callouts
- Brushed gold `#C9A961` — accents
- Pale gold `#E8D4A0` — links + hover
- Cream `#F5EFE4` — heading text
- Pearl `#C5BDA8` — body text
- Mist `#6B7080` — metadata / muted text
