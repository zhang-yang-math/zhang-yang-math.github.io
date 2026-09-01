# Yang Zhang — Academic Homepage

A small, dependency-free academic website built with HTML5 and CSS3. It is ready to be served directly from the root of a GitHub Pages repository.

## Files

- `index.html` — page content and semantic structure
- `styles.css` — responsive, dark-mode, focus, and print styles
- `notes/AGR.pdf` — GTM 52 exercise-answer notes
- `notes/deligne-riemann-hilbert-correspondence.pdf` — introductory notes on Deligne’s Riemann–Hilbert correspondence
- `assets/hero-image.png` — image displayed beside the homepage title
- `assets/papers/` — locally hosted publication PDFs
- `assets/slides/` — locally hosted talk slides
- `assets/` — site images, papers, and other static assets
- `robots.txt` — permits search-engine crawling and points to the sitemap
- `sitemap.xml` — identifies the canonical homepage URL for search engines
- `.nojekyll` — tells GitHub Pages to serve the static files without Jekyll processing

## Publish with GitHub Pages

1. Copy these files into the root of the repository's `main` branch.
2. On GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.

No package installation or build command is required.

## Search indexing

The canonical site URL is `https://zhang-yang-math.github.io/`. After publishing changes, submit that URL in Google Search Console and request indexing. Search engines may still take several days or weeks to include a new site.

## Content TODOs

- Add a CV file and navigation/contact link only when the CV is ready. No CV link is currently shown.
- Add the PDF for “Symmetry notions for toric Fanos” when it is available; its title is intentionally not linked yet.
- Replace the temporary shared arXiv link for the two toric papers when their individual arXiv pages are available.

## Local preview

Open `index.html` directly in a browser. A local web server is optional because all links use relative paths.
