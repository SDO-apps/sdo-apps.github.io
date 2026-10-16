<img src="assets/img/afield-icon.svg" alt="" width="48" height="48" />

# Afield Studio

The website for Afield Studio, an independent product studio. Live at **[afield-studio.github.io](https://afield-studio.github.io)**.

It's a static site (plain HTML, CSS, and a little JavaScript) served by GitHub Pages from `main`. There's no build step.

## Structure

```
index.html          Homepage: hero, work, about, closing
pillars/privacy/    Pillars privacy policy
pillars/terms/      Pillars terms of use
assets/css/site.css Shared styles for every page
assets/js/main.js   Header border on scroll, section reveal, footer year
assets/img/         Studio mark and product icons
```

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Adding a product

1. Add an `<article class="project">` to the Work section in `index.html`, with its icon in `assets/img/`.
2. If it needs legal pages, copy `pillars/` to `<product>/`, rewrite the text, and link them from the project and the footer.
