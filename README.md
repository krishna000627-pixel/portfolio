# Portfolio (v2)

Single-page site: "Krishna — apps I've built". Plain HTML, no build step, no dependencies. Images are embedded in `public/index.html`.

## Run locally
Open `public/index.html` in a browser (or `python3 -m http.server -d public`).

## Deploy
- **GitHub Pages (default):** `.github/workflows/deploy.yml` publishes `public/` on every push to `main`. Enable Pages once first: repo Settings > Pages > Source = "GitHub Actions" (the workflow cannot enable it itself). Private repos need a GitHub plan that allows Pages on private repos. Live at `https://<owner>.github.io/<repo>/`.
- **Vercel (optional):** import the repo; `vercel.json` already points to `public/`.

## Version
Shown in the site footer ("Portfolio vN") and in `<meta name="version">`. Bump both on every change.

## Environment variables / secrets
None.
