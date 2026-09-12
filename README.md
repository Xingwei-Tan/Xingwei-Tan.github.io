# Xingwei Tan — personal website

Source for [xingwei-tan.github.io](https://xingwei-tan.github.io), built with
[Jekyll](https://jekyllrb.com) on a fork of
[academicpages](https://github.com/academicpages/academicpages.github.io)
(itself a fork of [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes)).
Published automatically by GitHub Pages on push to `master`.

## Editing

| What | Where |
|---|---|
| Homepage (bio, news, selected publications) | `_pages/about.md` |
| CV | `_pages/cv.md`; the PDF is `files/cv.pdf` |
| Publications | one file per paper in `_publications/` |
| Nav menu | `_data/navigation.yml` |
| Name, bio, social links, site description | `author:` block in `_config.yml` |
| Colours | `_sass/_variables.scss` (`$primary-color`, `$info-color`) |

### Adding a publication

Create `_publications/paperN.md` with front matter only — no body is needed:

```yaml
---
title: "Paper Title"
collection: publications
category: conferences        # or: manuscripts (journal articles)
permalink: /publication/paperN
date: 2025-11-08             # controls ordering; newest first
venue: 'EMNLP 2025'
paperurl: 'https://aclanthology.org/2025.emnlp-main.1624/'
codeurl: 'https://github.com/...'   # optional
slidesurl: '...'                    # optional
citation: '**Xingwei Tan**, Co Author, and Third Author'
---
```

Wrap your own name in `**` so it is bold in the author list. Prefer stable URLs
(ACL Anthology landing pages, DOIs) over PDF or CDN links, which expire.

## Running locally

```bash
bundle install
bundle exec jekyll serve --livereload
# http://localhost:4000
```

Or with Docker:

```bash
docker build -t personal-site .
docker run -p 4000:4000 --rm -v $(pwd):/srv/jekyll personal-site
```
