# Only Chat website

Korean-first product and download page for Only Chat. The page is static HTML and CSS and deploys to GitHub Pages from `main` through `.github/workflows/pages.yml`.

## Downloads

The page currently marks macOS and Windows installers as **preparing**. Google Drive currently contains Only Chat source snapshots and Windows patches; those are not installers. The existing Mac wrapper build references a local source tree and is not a public distribution package. Keep the download states unchanged until a platform installer is built, validated, and uploaded to the intended Google Drive release folder. Then add the observed Drive file link, version, architecture, and checksum to the corresponding card.

## M-Oasis relationship

The page describes the product design relationship only. It does not connect to M-Oasis APIs, expose live task state, or read account information.
