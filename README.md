# Chaaya P A — Portfolio

A single-file HTML/CSS portfolio site. No build tools, no dependencies to install — just push it to GitHub.

## Put it on GitHub Pages (get a live link)

1. Go to github.com and create a new repository — name it `portfolio` (or anything you like).
   - If you want the link to be `https://chaayapa.github.io` exactly, name the repo `chaayapa.github.io` instead.
2. Upload `index.html` to the repo (drag-and-drop on the GitHub website works, or use `git`).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
5. Wait a minute, then your site is live at:
   - `https://chaayapa.github.io/portfolio/` (if you named the repo `portfolio`), or
   - `https://chaayapa.github.io/` (if you named the repo `chaayapa.github.io`)

## Editing content

Everything is in `index.html` — text, layout and styling are all in that one file, organized by section (`<section id="about">`, `<section id="projects">`, etc.). Open it in any text editor and change the text between the tags.

To link a real project to its GitHub repo, wrap the project title in an `<a>` tag, e.g.:

```html
<h3><a href="https://github.com/chaayapa/lecture-logger" target="_blank" rel="noopener">Lecture Logger</a></h3>
```

## Notes

- Fonts (Fraunces, Space Mono, Inter) load from Google Fonts via a CDN link in the `<head>` — no local font files needed.
- Fully responsive; tested down to mobile widths.
- No images are required to run — if you'd like a photo, add it to the repo and reference it inside the `.hero` section.
