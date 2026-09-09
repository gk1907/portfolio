# Gaurav Kumar — Portfolio Site

A single static site: `index.html` + an `images/` folder. No build step, no dependencies.

## Preview locally
Just double-click `index.html`, or run:
```
python3 -m http.server 8000
```
and open http://localhost:8000

## Deploy on GitHub Pages (free)

1. Create a new GitHub repository — e.g. `portfolio` (or `<your-username>.github.io` if you want it at the root of your GitHub domain).
2. Upload `index.html` and the whole `images/` folder to the repo root (drag-and-drop works on github.com — no git command line required, though learning `git add / commit / push` is worth it long-term).
3. In the repo: **Settings → Pages → Source → Deploy from a branch → branch: main, folder: / (root) → Save**.
4. GitHub gives you a live URL in a minute or two:
   - `https://<your-username>.github.io/portfolio/` (repo method), or
   - `https://<your-username>.github.io/` (if the repo is named `<your-username>.github.io`)

## Deploy on Netlify (alternative, no git required)

1. Go to app.netlify.com → "Add new site" → "Deploy manually"
2. Drag the whole `site` folder (containing `index.html` and `images/`) into the browser
3. Netlify gives you a live URL immediately; you can rename the subdomain or attach a custom domain for free

## Editing content later
Everything is in `index.html` — text is plain HTML, styling is in the `<style>` block at the top. No templating system, so search-and-replace works fine for text edits.
