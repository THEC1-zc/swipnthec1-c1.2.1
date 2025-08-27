
# SWIP Website Starter (Vercel-ready)

This is a minimal static site to use `swipnthec1.universe` as a website + file hub.

## Structure
- `index.html` — homepage (auto-lists files based on `files/manifest.json`)
- `files/` — put any files here (png, jpg, pdf, json, etc.)
- `files/manifest.json` — controls what appears on the homepage list
- `assets/` — optional images/icons for the site

## How to deploy on Vercel
1. Create a new project on Vercel and import this folder (or drag & drop).
2. After it deploys, you'll get a URL like `https://<project>.vercel.app`.
3. In Vercel → Project Settings → Domains, add `swipnthec1.universe` later.
4. In Freename, add a CNAME pointing `@` to Vercel (e.g. `cname.vercel-dns.com`).

## How to add files
- Drop files into `/files`.
- Update `/files/manifest.json` to include them so they show on the homepage.
- Even without the manifest, files are accessible directly by URL, e.g. `/files/mydoc.pdf`.
