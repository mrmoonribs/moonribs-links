# mrmoonribs links

This repository contains a self-contained static export of the mrmoonribs Signal Directory. The `site/` directory is published through GitHub Pages by the workflow in `.github/workflows/deploy-pages.yml` whenever changes are pushed to `main`.

## Local preview

Serve the `site/` directory with any static-file server. The export includes its JavaScript bundle and visual assets, so it does not depend on the previous hosting environment.

## Custom domain

Once the GitHub Pages URL is available, add `mrmoonribs.xyz` in the repository’s **Settings → Pages → Custom domain** panel. GitHub will display the exact DNS record needed for the domain cutover. Do not change the current DNS records until the GitHub Pages address has been tested.
