# Afield Studio

Company site and app legal pages, hosted on GitHub Pages.

## Adding an app

1. Copy `pillars/` to `<app>/` (lowercase, no spaces) and rewrite `privacy/index.html` and `terms/index.html` for that app.
2. Add a `.project` entry for it under **Work** in `index.html`, linking `<app>/privacy/` and `<app>/terms/`.
3. Use `https://<this site>/<app>/privacy/` as the app's privacy policy URL in App Store Connect and in the app.

All pages share `assets/css/site.css`; legal pages use the `.doc-layout` / `.doc` styles so every app's pages look the same.
