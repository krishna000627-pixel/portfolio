# Portfolio (v1)

Single-page site: "Krishna — apps I've built". Plain HTML, no build step, no dependencies. Images are embedded in `public/index.html`.

## Run locally
Open `public/index.html` in a browser (or `python3 -m http.server -d public`).

## Deploy
- **GitHub Pages (default):** `.github/workflows/deploy.yml` publishes `public/` on every push to `main`. If the first run says Pages is not enabled, open the repo Settings > Pages and set Source to "GitHub Actions", then re-run. Live at `https://<owner>.github.io/<repo>/`.
- **Vercel (optional):** import the repo; `vercel.json` already points to `public/`.

## Version
Shown in the site footer ("Portfolio vN") and in `<meta name="version">`. Bump both on every change.

## Environment variables / secrets
None.
