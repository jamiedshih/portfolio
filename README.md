# Jamie Shih — Portfolio

Personal portfolio site (plain HTML + CSS, no build step), deployed with GitHub Pages via `.github/workflows/static.yml`.

## Before you publish — fill these in
- [ ] **Résumé:** add your PDF to the repo root as `resume.pdf` (the Résumé buttons link to it).
- [ ] **LinkedIn:** in `index.html`, search for `YOUR-LINKEDIN` and paste your profile URL.
- [ ] **Coursework / GPA:** edit the "Relevant coursework" chips in the Education section; add GPA if ≥ 3.3.
- [ ] **Project photos (optional):** drop images in `images/` and swap the `<svg>` inside a project's `.card__media` for `<img src="images/….jpg" alt="…">`.
- [ ] **Project links:** uncomment the `View code →` link on a card once its repo is public.

## Turn on GitHub Pages
Repo → Settings → Pages → Source: **GitHub Actions**. Every push to `main` redeploys to
`https://jamiedshih.github.io/portfolio/`.

## Editing
- Colors/fonts: the variables at the top of `style.css`.
- Add a project: copy an `<article class="card">` block in `index.html`.
- Add a job: copy an `<li class="job">` block in the Experience timeline.
