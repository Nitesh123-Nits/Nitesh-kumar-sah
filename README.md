# Nitesh Kumar Sah · Portfolio

Personal portfolio site: a single static page (`index.html`) with no build step and no dependencies apart from Google Fonts.

**Live:** https://nitesh123-nits.github.io/Nitesh-kumar-sah/

## Features
- Flat, minimal design with a light/dark toggle (follows the system setting by default, remembers the choice)
- Responsive down to small phones
- SEO basics: title, description, Open Graph tags and `schema.org` Person JSON-LD

## Run locally
Open `index.html` in a browser, or serve the folder:
```bash
python3 -m http.server 8000
```

## Deploy (GitHub Pages)
Push to `main`, then enable **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`**. The site is served at `https://nitesh123-nits.github.io/Nitesh-kumar-sah/`.

## Updating content
Everything lives in `index.html`: experience in `#experience`, projects in `#projects`, skills in `#skills`.
