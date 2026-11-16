# ricamaesupa-portfolio

Portfolio site for Rica Mae G. Supa — ICT & Computer Science Teacher / Virtual Assistant.

Live: https://ricamaesupa-portfolio.pages.dev/

## What this repo is

This is the built site recovered from the live Cloudflare Pages deployment (Oct 26, 2026), because the original Next.js source was not in Cloudflare — only the built static files were there. Cloudflare Pages was a direct upload, with no Git connection and no build settings.

So this repo holds the deployed static output (HTML, CSS, JS, images), not the original Next.js source. Future edits are made to these HTML files directly.

## Deploy

Cloudflare Pages, direct from this GitHub repo:

- Framework preset: None / Static
- Build command: (none)
- Build output directory: (root /)
- Production branch: main

Push to `main` and Cloudflare redeploys automatically once connected.

## Structure

- `index.html` — homepage
- `blog/` — blog index + 24 posts
- `projects/`, `services/`, `tools/` — section pages
- `assets/` — photos and project images
- `_next/` — Next.js static-export assets (JS, CSS, fonts)
- `favicons/`, `sitemap.xml`, `robots.txt`, `404.html`
