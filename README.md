# alicciardi

Personal academic website for Alessandro Licciardi.

Published at: **https://alelicciardi99.github.io/alicciardi**

## Structure
- `index.html` — single page, anchor navigation (About / Research / Talks / Teaching / Service / Contact + CV).
- `styles.css` — styling.
- `assets/` — figures, photo, and the public CV (`cv_public.pdf`).
- `.nojekyll` — tells GitHub Pages to serve files as-is (no Jekyll processing).

## Base URL
This is a **project** repository, so the site is served under the sub-path `/alicciardi/`.
All internal links are same-page anchors (`#about`, …) and all asset references are
**relative** (`assets/…`), so they resolve correctly both locally and at
`https://alelicciardi99.github.io/alicciardi` without any base-URL rewriting.

## Publish (GitHub Pages)
1. Push this directory to the `main` branch of `alelicciardi99/alicciardi`.
2. Repository → Settings → Pages → Build and deployment:
   - Source: **Deploy from a branch**
   - Branch: **main** / **/ (root)**
3. The site goes live at https://alelicciardi99.github.io/alicciardi
