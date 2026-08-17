# Ngong Marinus Ngong — Portfolio

Personal portfolio of **Ngong Marinus Ngong** — Full-Stack Django Engineer and Chief Product Officer at FerdsiLinks, building OHADA/SYSCOHADA-2018-compliant ERP and fintech software for Francophone Africa and the CEMAC region.

🔗 **Live site:** https://ngongmarinus.github.io/ngongmarinus.com/

---

## About

A single-page, fully responsive portfolio built around real production work — most notably **Solafide (SOAS)**, a multi-tenant, offline-first, bilingual (FR/EN) accounting & business platform.

### Highlights

- ⚡ **Zero build step** — one self-contained `index.html`, deploys straight to GitHub Pages
- 🌗 **Light / dark theme** toggle (remembers your choice via `localStorage`, respects system preference)
- 🎨 Gradient-mesh hero, glassmorphic navigation, animated counters, typed role rotation
- 🧩 Authentic tech marquee via [Devicon](https://devicon.dev/)
- 📱 Mobile-first responsive — clean from **360px** to **1440px+**
- ♿ Reduced-motion support and accessible tap targets

## Tech stack (this site)

| Layer | Tools |
|-------|-------|
| Markup | HTML5 |
| Styling | [Tailwind CSS](https://tailwindcss.com/) (CDN), custom CSS |
| Fonts | Sora + Inter (Google Fonts) |
| Icons | Font Awesome 6, Devicon |
| Behaviour | Vanilla JavaScript (no framework) |
| Hosting | GitHub Pages |

> The **Solafide** platform showcased on the site is built with Python, Django, Django REST Framework, django-ledger, PostgreSQL, Celery, Redis, Django Channels, Docker, and more.

## Run locally

No dependencies or build tools required — it's a static file.

```bash
# clone
git clone https://github.com/Ngongmarinus/ngongmarinus.com.git
cd ngongmarinus.com

# open directly...
start index.html          # Windows

# ...or serve it (recommended, so fonts/CDN load cleanly)
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

The site is served from the **`main`** branch (root folder) via GitHub Pages.
Any push to `main` redeploys automatically within a minute or two:

```bash
git add .
git commit -m "update portfolio"
git push
```

## Contact

- **Email:** ngongmarinus273@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/marinus-ngong-86757b30b
- **GitHub:** https://github.com/Ngongmarinus
- **Product:** https://app.solafideonline.com
- **Location:** Buea, Cameroon

---

© Ngong Marinus Ngong. All rights reserved.
