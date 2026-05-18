# Ibrahim Khaleelulla Mohammad — Portfolio

Personal portfolio site for **Ibrahim Khaleelulla Mohammad**, Data Scientist & Generative AI Engineer.

Live site: _coming soon via GitHub Pages_

## Tech

- Single-file HTML / CSS / vanilla JS — no build step, no dependencies
- Dark-mode "developer" aesthetic with smooth scroll, reveal animations, and tabbed experience section
- Fully responsive (desktop, tablet, mobile)
- Google Fonts: Inter + JetBrains Mono

## Run locally

Just open `index.html` in any browser. That's it.

```bash
# optional — serve over http (helps with some browser caching)
python -m http.server 8000
# then open http://localhost:8000
```

## Editing

Everything lives in `index.html`. The most common things you'll want to change:

| What | Where to look |
|------|---------------|
| Name / tagline | `<section class="hero">` near the top of `<body>` |
| About text | `<section id="about">` |
| Skills tags | `<section id="skills">` — duplicate any `.skill-card` block to add a category |
| Experience bullets | `<section id="experience">` — each role is an `.exp-content` block |
| Projects | `<section id="projects">` — duplicate a `.project-card` to add a new one |
| Education | `<section id="education">` |
| Email / phone | search `ibrahimkhmd999@gmail.com` and `2695508269` |
| LinkedIn link | search `linkedin.com` in the `.rail.left` block |
| Colors / theme | `:root` CSS variables at the top of the `<style>` block |

## Deploy to GitHub Pages

1. Push this folder to a new GitHub repo (see below)
2. Repo → **Settings** → **Pages**
3. Source: **Deploy from a branch** → Branch: `main` / folder: `/ (root)` → **Save**
4. After ~1 minute the site is live at `https://<your-username>.github.io/<repo-name>/`

## Contact

- Email: ibrahimkhmd999@gmail.com
- Phone: (269) 550-8269
