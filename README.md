# sparkplugseo-site

Static one-page website for **SparkPlug SEO** — Jessica Schmukler, solo SEO & AI Search specialist (sparkplugseo.com).

Single `index.html` with inline CSS + vanilla JS. No build step, no framework. Deployed via **Cloudflare Pages** from `main`.

## Before going live — replace these placeholders in `index.html`

| Placeholder | Where | Get it from |
|---|---|---|
| `YOUR_WEB3FORMS_ACCESS_KEY` | contact `<form>` | https://web3forms.com (free; set delivery to jessie@sparkplugseo.com) |
| `YOUR_TURNSTILE_SITE_KEY` | `.cf-turnstile` div | Cloudflare → Turnstile → Add site |
| `G-XXXXXXXXXX` (×2) | `<head>` GA4 snippet | Google Analytics 4 → Admin → Data streams |

## Files
- `index.html` — the site
- `robots.txt`, `sitemap.xml` — crawl/index
- `site.webmanifest`, `favicon.ico`, `favicon.svg`, `apple-touch-icon.png` — icons/PWA
- `assets/og-image.png` — 1200×630 social share card
- `_headers` — Cloudflare cache + security headers

Deployed via Cloudflare Pages from `main`.
