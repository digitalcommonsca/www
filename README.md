# Canadian Digital Commons Institute Jekyll Site

A Jekyll conversion of the approved `cdci-distinct-site-v3` design, with a complete blog structure.

## Included

- Distinctive fixed-rail desktop design and responsive mobile navigation
- Jekyll layouts and includes
- Blog index and individual post layout
- Three publication-ready sample posts
- Homepage latest-writing section
- Jekyll SEO Tag, Atom feed, and sitemap support
- Custom 404 page
- Responsive typography and article styling

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000`.

## Before publishing

Update `url` and `baseurl` in `_config.yml` once the final domain and deployment path are known.

## Writing a new post

Create a file in `_posts` using this filename format:

```text
YYYY-MM-DD-post-title.md
```

Use front matter such as:

```yaml
---
title: Post title
description: A concise summary.
category: Research
---
```
