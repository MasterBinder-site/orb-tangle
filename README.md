# Orb Tangle website

Static GitHub Pages site for Orb Tangle. It uses only HTML, CSS and a small SVG mark; no build step or tracking script is required.

## Pages
- `index.html` — home page
- `marketing.html` — game overview
- `support.html` — how to play, hints and FAQs
- `privacy.html` — privacy policy

## Publish
Publish the `main` branch from the repository root in **Settings → Pages**. This is a project site, so links are relative to the repository path.

## app-ads.txt
The copy in this repository is served beneath `/orb-tangle/app-ads.txt`. AdMob looks at the root of the developer website’s host, not this project subpath. The existing `https://masterbinder-site.github.io/app-ads.txt` already contains the Orb Tangle publisher line; keep that root file unchanged. Register `https://masterbinder-site.github.io/orb-tangle/` as the developer website so the crawler resolves the shared root file.

## Before App Store submission
Complete App Store Connect metadata, including the age-rating questionnaire and privacy disclosures, against the shipped build and its SDKs. The App Store button remains disabled until the official listing URL is available. Confirm the AdMob developer website and crawler status in AdMob; serving `app-ads.txt` does not by itself confirm crawler verification.
