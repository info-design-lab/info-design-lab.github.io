# Information Design Lab Site

This repository contains the Information Design Lab website (https://info-design-lab.github.io) built with Hugo. Older legacy root-site files have been preserved in `archive/info-design-lab-site-v1/`.

## Table of Contents

- [Structure](#structure)
- [Adding Content](#adding-content)
	- [Add an article](#add-an-article)
	- [Edit the main page](#edit-the-main-page)
	- [Add a page](#add-a-page)
	- [Add a homepage section](#add-a-homepage-section)
- [Hextra Theme Documentation](#hextra-theme-documentation)
- [Local Development](#local-development)

## Structure

- `content/_index.md`: homepage content and homepage sections
- `content/articles/`: article index and individual article pages
- `assets/css/custom.css`: site-specific styling
- `layouts/`: Hugo partials and shortcodes used by the site
- `.github/workflows/pages.yaml`: GitHub Pages deployment workflow

## Adding Content

### Add an article

Create a new `.md` file in `content/articles/`.

Example:

```md
---
title: "Article Title"
date: 2026-04-27
summary: "Short summary used in article previews."
author: "Venkatesh Rajamanickam"
source: "LinkedIn"
---

{{< article-byline >}}

<p class="article-read-link"><a href="https://www.linkedin.com/..." target="_blank" rel="noreferrer">Read on LinkedIn</a></p>

Full article text here.
```

Articles automatically appear:

- on the `/articles/` page as previews
- in the homepage Articles preview section


### Edit the main page

The main homepage content lives in `content/_index.md`.

Use this file to edit:

- the hero/banner text
- About, Research & Teaching, Internships, People, and Contact sections
- homepage-only links and layout content

Changes to `content/_index.md` are published on the site homepage at `https://info-design-lab.github.io/`.

### Add a page

Create a new `.md` file under `content/`.

Example:

```md
---
title: "New Page"
---

Page content here.
```

The page will be available at a URL based on its file name. For example, `content/about.md` becomes `https://info-design-lab.github.io/about/`.

### Add a homepage section

Edit `content/_index.md` and add the new section in Markdown or HTML. Update `hugo.yaml` if the section should be linked from the navbar.

## Hextra Theme Documentation

Hextra docs: https://imfing.github.io/hextra/docs/


## Local Development

Prerequisites:

- Hugo extended
- Go
- Git

Run locally from the repository root:

```sh
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

Then open `http://localhost:1313`.

To create a production build locally:

```sh
hugo
```

