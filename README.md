# Kaiwen Zhu · Personal website

Live at https://kaiwenzhu.com/.

A small, responsive academic-style homepage using plain HTML and CSS. No JavaScript, external fonts, package installation, or build framework is required.

## Edit

- `index.html`: biography, profile links, and project entries. Add publications once the actual details are available; do not publish sample research as personal work.
- `assets/style.css`: layout, colors, and responsive styles.
- Replace the `.portrait` monogram with a real image when ready, and give it descriptive alt text.
- `CNAME`: custom domain. Keep this unless intentionally changing domains.

To add a project, duplicate the existing `article.project`, change the title, description and link, and replace its decorative preview with an image with an appropriate alt attribute.

## Preview and publish

Run `python3 -m http.server 8765` from this folder and open http://localhost:8765. Pushing `main` automatically publishes the public files through GitHub Pages. Only the allowlisted site files and asset folders are deployed.

Previous al-folio implementation is preserved on the `al-folio-site` branch. Legacy `/projects/` and `/publications/` links redirect to the homepage.
