# outerhome-site

Static site for [outerhome.co](https://outerhome.co).

## Layout

All served files sit at the repository root: 37 HTML pages plus `robots.txt` and
`sitemap.xml`. Each page is self-contained — inline CSS, inline JS, base64-embedded
images — so there is no build step.

## Deploying

Pushing to `main` triggers a Cloudflare Workers build that deploys this repo to the
`outerhome-site` Worker serving outerhome.co.

## Pages

- `index.html` — homepage
- Services: `roofing`, `siding`, `windows`, `gutters`
- 28 city landing pages
- `installers.html`, `join-the-family.html`
- `privacy.html`, `terms.html`
