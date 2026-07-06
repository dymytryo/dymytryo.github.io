# dymytryo.github.io

Personal portfolio for **Dmytro Valiaiev** — Staff Data Engineer. Static HTML/CSS, no build step, hosted on GitHub Pages.

## Pages

- `index.html` — home (hero, metrics, featured work, skills, experience)
- `projects.html` — full project index
- `about.html` — background, experience timeline, education, certifications
- `case-studies/` — deep-dive write-ups (e.g. the lead-optimization pipeline)
- `assets/style.css` — all styling (Direction B: editorial light)
- `assets/` — résumé PDF, deck PDF, favicon, link-preview image

## Editing (no tools required)

Open any `.html` file and edit the text between the tags. To add a project, copy one `<article class="project"> … </article>` block in `projects.html`, change the title, description, tags, and link, then save.

All colors and fonts live in one place — the `:root` block at the top of `assets/style.css`.

## Deploy

Commit and push to the `main` branch. GitHub Pages serves it at <https://dymytryo.github.io> and updates within about a minute.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server
# then visit http://localhost:8000
```

## Design

Editorial (light): warm off-white canvas, Fraunces serif headings, terracotta accent, generous whitespace. Fully responsive and accessible (semantic HTML, skip link, focus states, reduced-motion support).
