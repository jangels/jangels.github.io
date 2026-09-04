# jangels.github.io

Personal site of **shapefire (jangels)** — _You Shaper = Philosophy + Art + Architect_.

Built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

## Structure

- `_config.yml` — site settings (no theme gem / no plugins, fully self-contained)
- `_layouts/` — `default`, `home`, `page`, `post` (custom, no external theme dependency)
- `index.md` — home page (`layout: home`)
- `about.md` — about page (`layout: page`)
- `_posts/` — blog posts (`layout: post`)
- `assets/css/style.css` — site styles

## Local preview (optional)

This site intentionally ships **no Gemfile** so GitHub Pages builds it with its
default Jekyll toolchain (bulletproof, zero external gem dependency). For a
local preview you can install Jekyll and serve directly:

```bash
# macOS (or use a Ruby version manager)
gem install jekyll
jekyll serve
```

Then open http://localhost:4000.
