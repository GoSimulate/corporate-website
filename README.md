# GoSim Corporate Website

The website for GoSim Limited — [gosimulate.com](https://gosimulate.com/).

Hand-written static HTML/CSS: no framework, no build step, no JavaScript, and no external
requests (system font stacks, inline SVG favicon). Open `index.html` in a browser, or serve the
directory with any static file server:

```sh
python3 -m http.server 8000
```

## Structure

- `index.html` — single-page site: hero, What We Do, Who We Are, footer
- `privacy.html` — privacy notice
- `styles.css` — shared stylesheet (dark technical theme, brand blue `#00B0F0`)
- `favicon.svg` — blue "O" mark on a dark tile
- `robots.txt` — crawl policy

## Deployment

Served as static files via GitHub Pages: the repository root is the site root, with no build
step.
