# Panibhate Shiva Prasad — Portfolio

Static portfolio site (HTML + CSS + vanilla JS). No build step.

## Structure
- `index.html` — the whole site
- `assets/cover.jpg` — hero background photo
- `assets/Shiva_Prasad_Resume.pdf` — resume linked from "View Resume"

## Before publishing
Replace the placeholder links in `index.html`:
- `https://www.linkedin.com` -> your LinkedIn profile URL
- `https://github.com` -> your GitHub profile URL
(search for these two in the file; each appears in the hero and contact section)

## Deploy on GitHub Pages
1. Create a new repo on github.com (e.g. `portfolio`, or `<username>.github.io` for a root URL).
2. In this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<username>/<repo>.git
   git push -u origin main
   ```
3. On GitHub: Repo -> Settings -> Pages -> Source: "Deploy from a branch" -> Branch: `main`, folder `/ (root)` -> Save.
4. After ~1 minute the site is live at `https://<username>.github.io/<repo>/`.
