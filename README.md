# Kaiwen Zhu

Live: https://kaiwenzhu.com/

Uses the official static HTML edition of [Minimal Light](https://github.com/yaoyao-liu/minimal-light), upstream revision `1ea07f39518ac44644406380c83da6f89037c4fc`. This is the theme's HTML distribution, not a Jekyll build. Original theme styles are in `assets/minimal-light.css`; local adjustments are in `assets/style.css`. Google font imports were removed to use local system fonts. Theme license: `licenses/minimal-light-CC0.txt`.

## Add content gradually

Edit `index.html`. Add each real section inside the corresponding `<section>` in `<main>`. The page intentionally has no sample biography, publications, project, footer slogan, or placeholder image.

For example, add an h2 and paragraphs for About, then add Publications or Projects when their contents are ready. Do not publish the theme author's sample credentials or papers.

## Social icons

Email, Google Scholar, GitHub, LinkedIn, and Twitter are available as local SVG icons. GitHub and Google Scholar are enabled. Find the relevant `data-social` entry, add its real `href`, then remove `hidden`. For email use `mailto:your-address`. Keep unused entries hidden.

## Preview and publish

Run `python3 -m http.server 8765`, then visit http://localhost:8765. Pushing `main` deploys with GitHub Pages. Keep `CNAME` unchanged. Legacy projects/publications links return to the homepage.
