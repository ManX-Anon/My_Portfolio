# Portfolio — Vivek Yadav

A minimal, professional portfolio site built with plain HTML, CSS, and JavaScript — no build step, no dependencies.

## Files

```
index.html   structure and content
style.css    all styling
script.js    scroll-reveal animation (progressive enhancement only)
```

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create a new repository (e.g. `portfolio`) and push these files to the `main` branch.
2. In the repo, go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)`, then save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

To use it as your profile site (`https://<your-username>.github.io`), name the repository exactly `<your-username>.github.io`.

## Customizing

- Update text, links, and the certification/writeup lists directly in `index.html`.
- Colors, type, and spacing are all controlled by CSS custom properties at the top of `style.css` (`:root { ... }`).
