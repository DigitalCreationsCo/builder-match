# Builder Match

A one-page brief: find the best solo builders on X and offer them a shot at a 10X+ outcome at a speedrun company.

**Live page:** https://digitalcreationsco.github.io/builder-match/

## Structure

- `index.html`: the whole page in one static file with inline CSS. Fonts come from Google Fonts (Instrument Sans). It switches between light and dark mode with `prefers-color-scheme`.
- `.nojekyll`: tells GitHub Pages to serve the files as they are, without a Jekyll build.

## Deployment

GitHub Pages serves the site from the `main` branch root (`/`). Every push to `main` redeploys it.

To preview locally, open `index.html` in a browser, or run `python3 -m http.server` and go to http://localhost:8000.
