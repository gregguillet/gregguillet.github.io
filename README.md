# Grégoire Guillet — Academic Website

A Jekyll-powered GitHub Pages site.

## Quick Setup

1. Create a repo named `yourusername.github.io` on GitHub
2. Upload **all** these files into the root of that repo
3. Add your photo as `assets/images/photo.jpg`
4. Go to repo **Settings → Pages** → set source to `main` branch
5. Wait ~2 minutes, then visit `https://yourusername.github.io`

## File Structure

```
.
├── _config.yml          # Site configuration & navigation
├── _layouts/
│   └── default.html     # Main layout template
├── _posts/              # Blog posts (shown as dates in nav)
├── assets/
│   ├── css/style.css    # Site styling
│   └── images/photo.jpg # Your photo
├── index.md             # Home page
├── research.md          # Research page
├── publications.md      # Publications page
└── about.md             # About / CV page
```

## Editing Content

All pages are Markdown (`.md` files). Just edit:

- `index.md` — Home page (bio, research interests)
- `research.md` — Research details
- `publications.md` — Publication list
- `about.md` — CV / About page

## Adding Blog Posts

Create a new file in `_posts/` named `YYYY-MM-DD-title.md` with front matter:

```yaml
---
layout: default
title: "Your Post Title"
date: YYYY-MM-DD
---
```

Post dates automatically appear in the navigation bar.

## Customisation

- **Site title/URL**: Edit `_config.yml`
- **Styling**: Edit `assets/css/style.css`
- **Layout/nav**: Edit `_layouts/default.html`
