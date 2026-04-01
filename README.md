# RewardLedger Marketing

This repository hosts the public marketing website for RewardLedger.

## Purpose

- Provide a public website URL for the iOS app listing.
- Publish required ad-authorization information for ad network verification.
- Keep compliance-facing content separate from the main app codebase.

## Netlify Deployment

This site is structured for root-domain hosting on Netlify.

- Home: `/`
- Support: `/support/`
- Privacy: `/privacy/`
- Terms: `/terms/`
- Ad authorization: `/app-ads.txt`

All internal links and stylesheet references use root-based URLs (for example, `/support/`, `/assets/styles.css`) so navigation works on a normal hosted domain (including `*.netlify.app`).

## AdMob app-ads.txt

`app-ads.txt` is published at the site root and must remain continuously accessible:

- `https://<your-site>/app-ads.txt`

Use the same hostname in your App Store listing website URL so AdMob can crawl it correctly.

## Ownership

Maintainer: RewardLedger project owner
