# outerhome-site

Static site for [outerhome.co](https://outerhome.co).

## Layout

- `public/` — everything that gets served. 37 HTML pages plus `robots.txt` and `sitemap.xml`.
  Each page is self-contained: inline CSS, inline JS, base64-embedded images.
- `wrangler.jsonc` — Cloudflare Workers config. Points the Worker at `public/`.

## Deploying

Pushing to `main` triggers a Cloudflare Workers build, which deploys `public/` to the
`outerhome-site` Worker serving outerhome.co. No build step runs — the files are shipped as-is.

## Pages

- `index.html` — homepage
- Services: `roofing`, `siding`, `windows`, `gutters`
- 28 city landing pages
- `installers.html`, `join-the-family.html`
- `privacy.html`, `terms.html`
