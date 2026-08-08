# Direwolf Cybersecurity — marketing site + blog

Static site served by GitHub Pages at
**https://www.direwolfcybersecurity.com**.

- `index.html` — the homepage (styles, scripts, and images are embedded in this one file)
- `CNAME` — tells GitHub Pages which custom domain to serve this site on
- `_posts/` — blog posts, one Markdown file each (see `HOW-TO-POST.md` for the
  step-by-step publishing guide)
- `_layouts/`, `blog/`, `assets/`, `_config.yml` — blog pages, styling, and
  Jekyll configuration (GitHub Pages builds these automatically)

To update the live site: edit files, commit, and push to `main` (or edit
directly on GitHub). The site rebuilds automatically; allow up to ~10 minutes
for the build plus cache refresh.

The client portal / platform is a separate, private repository (`direwolf`).
