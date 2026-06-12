# Personal Website — Pedro Durval

Static personal website built with plain HTML, CSS and JavaScript — no build step required. Designed to be hosted on [GitHub Pages](https://pages.github.com/).

## Structure

- `index.html` — single-page site (hero, experience, education, publications, skills, contact)
- `styles.css` — styling, with dark/light theme support
- `script.js` — theme toggle and scroll-reveal animations

## Publishing on GitHub Pages

1. Create a GitHub repository named `<username>.github.io` (the site will live at `https://<username>.github.io`), or any other repo name (the site will live at `https://<username>.github.io/<repo>`).
2. Push this folder to the repository's `main` branch.
3. In the repository settings, go to **Pages** and set the source to **Deploy from a branch** → `main` / root.
4. The site goes live within a couple of minutes.

## Local preview

Just open `index.html` in a browser, or serve the folder:

```sh
python -m http.server 8000
```
