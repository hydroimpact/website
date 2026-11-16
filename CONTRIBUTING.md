# Contributing to the HydroImpact website

Thanks for helping. Most contributions are one of the following.

## Suggest a paper

The papers page is hidden until the first entries are added, but suggestions are already welcome.

The easiest way is to open a [Suggest a paper](https://github.com/hydroimpact/website/issues/new?template=suggest-paper.yml) issue.

If you are comfortable with GitHub, you can instead add an entry to `data/papers.yaml` in a pull request. The fields are described at the top of that file. Use the DOI without the `https://doi.org/` prefix.

## Write a news post

Create a Markdown file in `content/news/`, named `YYYY-MM-short-title.md`:

```markdown
---
title: Short, descriptive title
date: 2027-04-01
description: One sentence shown in the news list.
draft: true
---

Text of the post.
```

Keep `draft: true` while you work on it. Drafts are not published; remove the line when the post is ready.

## Preview your changes

Install [Hugo](https://gohugo.io/installation/) (version 0.170 or later), then run from the repository root:

```bash
hugo server -D
```

and open <http://localhost:1313>. The `-D` flag also shows drafts.

## Style

- Write for practitioners as well as researchers: short sentences, plain words, no unexplained acronyms.
- British English spelling.
- Sentence case for titles ("Results from the first co-design workshop", not "Results From The First...").
