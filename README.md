# 3 Friends and a Guy Named Travis

A movie directory organized by **how films make you feel** — not by stars, not by genre.
Sad, hyped, cozy, on edge, nostalgic, mind-blown, cathartic rage. You pick the feeling;
we point you at the movie.

Sponsored, reluctantly, by the podcast of the same name. (Long story. See the site.)

## What's here

This is a plain static website — no build step, no frameworks.

| File | Purpose |
|------|---------|
| `index.html` | The landing page |
| `styles.css` | All styling |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## View it locally

Just open `index.html` in your browser. Double-click it, or:

```bash
# optional: serve it on a local web server (needs Python)
python3 -m http.server 8000
# then visit http://localhost:8000
```

## How it's hosted

Hosted free on **GitHub Pages**. Any change pushed to the `main` branch goes live
automatically within a minute or two.

To make edits: change `index.html` / `styles.css`, then:

```bash
git add .
git commit -m "Describe your change"
git push
```
