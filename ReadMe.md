# Aniket Mahajan — Portfolio

A modern, responsive portfolio built with plain HTML, CSS, and vanilla JavaScript. It has no framework, package manager, dependency installation, or build step, so it can be hosted directly with GitHub Pages.

## Files

- `index.html` — semantic page structure and portfolio content
- `css/portfolio.css` — styling, responsive layout, and motion effects
- `js/portfolio.js` — mobile navigation, reveal-on-scroll, and subtle pointer interactions
- `assets/` — existing portfolio images and resume assets

## Preview locally

Run from the repository root:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Deploy with GitHub Pages

In repository Settings → Pages, select the branch and folder containing `index.html` (usually the repository root). No build command is required.

Before publishing, replace the existing resume PDF in `assets/` with the current version you want to expose. The downloadable package accompanying this change includes both the Global and India resumes with links in the page.
