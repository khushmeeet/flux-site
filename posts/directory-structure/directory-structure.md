---
template: docs-detail
title: Directory Structure
---

## Directory Structure

Flux follows a fix directory structure. It looks somewhat similar to jekyll directory structure.

```bash
.
├── _site
├── assets
├── blog.html
├── config.json
├── css
├── index.html
├── posts
└── templates
```

```_site``` is where generated website lives. You can push this directory on Vercel or Netlify or any other cloud hosting, to host your website.

```assets``` stores images or logos for the website (global level assets).

```blog.html``` could be any html file, which will act as an individual webpage in the website, which can be linked to any other page like ```href="/blog/"```

```config.json``` is a flux configuration file.

```css``` holds SCSS file for styling the website.

```index.html``` is mandatory webpage, that acts as the front page.

```posts``` stores your blog posts or any other webpages, that is written in markdown.

```templates``` holds partials or base templates, that can be used in other html files.
