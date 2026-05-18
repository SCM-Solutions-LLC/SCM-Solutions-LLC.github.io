# SCM Solutions LLC — site deploy bundle

Drop these files into the root of:
  https://github.com/SCM-Solutions-LLC/SCM-Solutions-LLC.github.io

## What to do

1. **Replace** the existing `index.html` at repo root with this one.
2. **Add** these new files alongside it:
   - `brand.html` (internal brand & Play Store assets reference page — optional, but harmless to publish)
   - `styles.css`
   - `img/icon.jpeg`
   - `img/screenshot-tasks.png`
   - `img/scm-favicon.svg`
3. **Keep as-is** (do NOT delete):
   - `CNAME`
   - `robots.txt,`
   - `sitemap.xml`
   - `226506facf02039500b4288f5e71ff99.html` (your Google site-verification file)
   - `assets/` folder (if you have anything there you still use)

## Notes

- All SteadiDay links on the new site point externally to https://www.steadiday.com — no standalone SteadiDay page is included.
- The site uses Google Fonts (Source Serif 4, IBM Plex Sans, IBM Plex Mono) loaded over the network. No build step required.
- The Engagement Fit tool is pure HTML/CSS/JS — no backend needed; it generates a pre-filled mailto: link to contact@scmsolutions.org.

## Commit message suggestion

> Site redesign: editorial restyle, Engagement Fit tool, external SteadiDay link, brand assets page
