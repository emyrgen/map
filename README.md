# EMYRGEN MAP Investor Website v1.3

Source-only static website package for the EMYRGEN™ MAP / Magnetic Abrasive Polishing investor website.

## Version focus

Version 1.1 is rebuilt as a strict one-column vertical investor website:

- No side-by-side hero layout
- No two-column sections
- No multi-column card grids
- No proof-gallery mosaic
- No two-column form
- Every section, card, visual, metric, and roadmap step stacks vertically

## Deploying on GitHub Pages

1. Create or open the GitHub repository.
2. Upload all files from this package to the repository root.
3. Commit to the `main` branch.
4. Go to **Settings → Pages**.
5. Select **GitHub Actions** as the Pages source.
6. Push again if needed to trigger the workflow.

The `.github/workflows/deploy-pages.yml` file is included.

## Package contents

- `index.html` — complete static website
- `assets/` — optimized image assets
- `.github/workflows/deploy-pages.yml` — GitHub Pages deployment workflow
- `.nojekyll` — disables Jekyll processing

No `node_modules`, no `dist`, and no generated build artifacts are included.


## v1.3 typography update
- Reduced heavy heading/title weights to elegant medium weights.
- Softened large-heading letter spacing for a more premium investor-site feel.
