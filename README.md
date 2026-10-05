# Apisit Yearayong - Portfolio

Scroll-driven 3D "road trip" portfolio. Plain static site: one HTML file, no build step, no database, no env vars.

- `index.html` the site (Three.js loaded from cdnjs)
- `resume.pdf`, `og.png` linked from the page

Run locally: open `index.html`, or `npx serve .`
Deploy: import this repo in Vercel (Framework: Other, no build command, output dir `.`).
After deploy, set `og:image` / `twitter:image` in `index.html` to the full URL, e.g. https://YOUR-SITE.vercel.app/og.png
