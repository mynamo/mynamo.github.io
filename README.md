# Portfolio site

A single-page, clean-minimal portfolio for your data projects. No build step, no
framework — just `index.html`. Edit it in any text editor.

## Publish it at `mynamo.github.io` (free, ~5 minutes)

GitHub gives every account one free "user site" served from a specially named repo.

1. Create a new **public** repo named exactly **`mynamo.github.io`**.
2. Add `index.html` to it (and `resume.pdf` if you have one) — drag-and-drop via
   **Add file → Upload files**, or push from your computer.
3. Go to the repo's **Settings → Pages**. Under *Build and deployment*, set
   **Source: Deploy from a branch**, branch **main**, folder **/(root)**, Save.
4. Wait ~1 minute, then visit **https://mynamo.github.io** — that's your one URL.

To update later, just edit `index.html` and push; the site refreshes automatically.

## Before you publish — fill in the placeholders

Search `index.html` for `TODO` and update:

- **Résumé** — add a `resume.pdf` next to `index.html`, or change the two `resume.pdf`
  links to point at your CV (e.g. a Google Drive share link).
- **LinkedIn** — replace `https://www.linkedin.com/in/your-handle` with your profile.
- **Yearbook links** — confirm the live URL (`year-book.streamlit.app`) and the source
  repo URL (`github.com/mynamo/YearBook` — update if the repo name differs).
- **Topic Modeling demo** — once you deploy that Streamlit app, add a "Live demo" link
  in its card (copy the pattern from the Yearbook card).
- **chattea demo** — add a live link once it's hosted (Render / PythonAnywhere).
- **About paragraph** — personalize it with your background and what you're looking for.

## Custom domain (optional, later)

If you buy a domain (~$12/yr), you can point it at the site in **Settings → Pages →
Custom domain**. Until then, `mynamo.github.io` works perfectly and is resume-ready.

## Adding a new project later

Copy one `<div class="card">…</div>` block in the Projects section, change the title,
description, links, and tech stack. That's the whole workflow.
