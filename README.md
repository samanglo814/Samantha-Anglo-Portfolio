# Samantha-Anglo-Portfolio
Samantha Anglo's professional portfolio

A static portfolio site built with plain HTML, CSS, and JavaScript. It has no build step, so it can be hosted directly on GitHub Pages.

## Files
- `index.html`: all page content. Search for `[` and `TODO` to find placeholders to fill in.
- `styles.css`: styling. Colors are defined at the top (`--berry` is the accent).
- `script.js`: mobile menu and scroll effects.
- `assets/`: add these files:
  - `photo.jpg`: a photo for the About section
  - `Samantha_Anglo_Resume.pdf`: your resume
  - `projects/project-one.png`, `project-two.png`, `project-three.png`: project screenshots (16:10 works best)

To add a smaller project, copy a `<tr>` row in the "More projects" table in `index.html`.

## Run locally
```bash
python3 -m http.server 8000
```
Then open http://localhost:8000.

## Deploy with GitHub Pages
Push to GitHub, then go to **Settings → Pages → Deploy from branch → `main` / root**.
The site will be live at `https://samanglo814.github.io/Samantha-Anglo-Portfolio/`.
