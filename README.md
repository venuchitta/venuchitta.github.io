# venuchitta.github.io

Personal website and blog — built with [Jekyll](https://jekyllrb.com) and hosted on [GitHub Pages](https://pages.github.com).

## Local development

```bash
# Install dependencies (first time)
export GEM_HOME="$HOME/.gem"
export PATH="$GEM_HOME/bin:$PATH"
bundle install

# Serve locally with live reload
bundle exec jekyll serve --port 4000
# → http://localhost:4000
```

## Writing a new post

Create a file in `_posts/` with the format `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "Your Post Title"
date: 2026-02-21
categories: [Engineering]
tags: [systems, design]
excerpt: "A short summary shown in card previews."
---

Your content here...
```

## Site structure

```
_posts/          Blog posts (YYYY-MM-DD-title.md)
_layouts/        Page templates (default, page, post)
_includes/       Partials (header, footer)
assets/css/      Stylesheets
index.html       Homepage
about.md         About page
blog/            Blog index
projects.md      Projects page
experience.md    Work history
contact.md       Contact page
_config.yml      Jekyll configuration
```

## Deployment

Push to `main` — GitHub Pages builds and deploys automatically.
