# Jenny Cajahuanca — Portfolio

Personal portfolio site for Jenny Cajahuanca, Marketing Strategist (Sydney).

A single-page static site. No build step — `index.html` is the whole site.

## Local preview

Just open `index.html` in a browser, or run a tiny static server:

```bash
npx serve .
```

## Deploy (Vercel)

This repo is set up as a zero-config Vercel static deploy. Pushing to the
default branch on GitHub triggers an automatic redeploy.

## Structure

- `index.html` — the site
- `assets/` — portrait images used on the page
- `uploads/` — resume / PDFs (linked or downloadable)

The original Claude artifact (`*.dc.html` + `support.js`) is kept locally for
reference but excluded from the published site via `.gitignore`.
