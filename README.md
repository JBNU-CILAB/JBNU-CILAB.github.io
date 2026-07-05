# CILAB Homepage

Homepage of the Compiler Intelligence Lab (CILAB) at Jeonbuk National University.
Built with [Jekyll](https://jekyllrb.com/) and automatically built & deployed by GitHub Pages.

- **Live site**: https://jbnu-cilab.github.io/

---

## 🚀 Deployment

Just **push** to the `main` branch — GitHub Pages builds and deploys the site automatically.
You only need to check the following setting once on GitHub:

> **Settings → Pages → Build and deployment → Source** → **"Deploy from a branch"**,
> **Branch** → **`main` / `(root)`** → Save

Changes usually go live within 1–2 minutes after a push.

---

## ✏️ Editing Content (no HTML needed)

Most content lives in the `_data/` folder — edit those files only.

| What you want to do | File to edit |
|---|---|
| Add / update members (students) | `_data/members.yml` |
| Add publications | `_data/publications.yml` |
| Add projects | `_data/projects.yml` |
| Edit research area text | `_data/research.yml` |
| Lab name, professor, contact, menu | `_config.yml` |

Each file includes examples and comments — just copy an existing entry and change the values.

### Adding photos
- Professor photo: place it in `assets/img/` and set `pi.photo` in `_config.yml`.
- Member photos: place them in `assets/img/members/` and set each member's `photo:`.
- If no photo is provided, an initial-based avatar is shown automatically.

---

## 💻 Local Preview (optional)

Only needed if you want to preview changes locally before pushing.

```bash
# One-time setup (requires Ruby)
gem install bundler
bundle install

# Run local server → open http://localhost:4000 in your browser
bundle exec jekyll serve
```

---

## 📁 Project Structure

```
├── _config.yml        # Global site settings
├── _data/             # Members, publications, projects, research areas (edit here)
├── _layouts/          # Shared page skeleton
├── _includes/         # Header & footer
├── assets/css/        # Styles (design)
├── assets/img/        # Images & photos
├── index.html         # Home
└── people/research/publication/project/contact .html
```
