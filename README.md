# Future Farming — Testable GitHub Pages App

A premium-looking, mobile-friendly **interactive prototype** of Future Farming using the site's colour palette, logo and agricultural imagery. No Python installation, servers, accounts or API keys required to test it.

## Publish from GitHub (PC or phone)

1. Open your repository `future-farming-app` on GitHub.
2. Click **Add file → Upload files**.
3. Upload **all files in this folder to the repository root**, not the ZIP itself. Include `index.html`, `app.js`, `styles.css`, `manifest.webmanifest`, `sw.js`, images and `.nojekyll` (optional).
4. Click **Commit changes**.
5. Go to **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose **main** and folder **/(root)**, then **Save**.
6. When deployment completes, open:
   **https://YOUR-GITHUB-USERNAME.github.io/future-farming-app/**

> GitHub Pages availability for private repositories depends on the GitHub plan. If your account cannot publish a private repository, a public repository is typically required on GitHub Free. This code contains no passwords, personal contact information or production secrets.

## What works in the interactive demo

- Home dashboard and site-branded graphics
- Mobile and desktop navigation
- Marketplace search, category filtering and sorting
- Country selection (South Africa, Namibia, Botswana, Zimbabwe, Zambia and Kenya)
- Listing details and saved listings
- Posting a new listing, with an optional compressed photo
- Contact seller demonstration (saves an example enquiry)
- Auctions and sample bidding (not actual bids)
- Market overview with sample data and illustrative trend
- Articles and rural security feature
- Local demo profile and reset data
- Installable Progressive Web App (PWA) on supported browsers after HTTPS deployment

## Important limitations

**This is not a live commercial marketplace.** All sample items, prices, market data, auctions and articles are fictional or illustrative. User-generated listings, bids, profile information and messages are saved **only in the device's browser storage**. They are not shared across devices, sent to sellers, or saved on GitHub. There is no real user authentication, database, payment processing, admin moderation or real-time market feed yet.

For public launch, add a secure backend and database, user authentication, server-side photo storage, permissions, spam protection, moderation, and a verified live market-data provider. Do not collect real identity documents, payment details or sensitive information in this demo.

## Try it locally

You can double-click `index.html` for a basic preview (most features work), but GitHub Pages is needed for reliable service-worker caching and installability.

## Structure

```text
index.html
styles.css
app.js
manifest.webmanifest
sw.js
brand-logo.png
harvest-hero.webp
rural-security.webp
icon-192.png
icon-512.png
.nojekyll
README.md
```

## Ownership / attribution

Graphics were prepared for the Future Farming demo from the existing Future Farming website branding and selected imagery. Confirm that you hold the appropriate rights to those graphics before public commercial use.
