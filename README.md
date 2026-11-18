# HydroImpact website

The community website of HydroImpact, a hydrological climate impact platform funded by BRIDGE Discovery (grant 40B2-0_243611). Built with [Hugo](https://gohugo.io/) and published on GitHub Pages at <https://hydroimpact.org>.

## Where things are

| What | File |
| --- | --- |
| Home page text (headline, modelling chain labels, "Why it matters", "What we will build", full summary) | `content/_index.md` |
| Team list | `data/team.yaml` |
| Papers list (the page is hidden until it has entries, see `content/papers.md`) | `data/papers.yaml` |
| News posts | `content/news/` |
| Privacy notice | `content/privacy.md` |
| Site settings: contact email, grant number, LinkedIn page | `hugo.toml` |
| Newsletter sign-up (Infomaniak embedded form) | `layouts/_partials/signup.html` |
| Page templates | `layouts/` |
| Styles | `assets/css/main.css` |
| Funder logos in the footer (files in `static/logos/`) | `data/funders.yaml` |
| Institution logos under the team | `data/institutions.yaml` |
| Fonts (Instrument Sans, Source Serif 4, SIL Open Font License) | `static/fonts/` |
| Modelling chain figure on the home page | `layouts/_partials/chain.html` and `chain-icon.html` |
| Link preview image for LinkedIn (`static/og-image.png`; edit `design/og-image.html`, then re-render it at 1200x630, e.g. `chrome --headless --window-size=1200,630 --screenshot=static/og-image.png design/og-image.html`). A news post can use its own image with `image:` and `image_alt:` in its front matter. | `design/og-image.html` |

See [CONTRIBUTING.md](CONTRIBUTING.md) for adding papers and news posts.

## Preview locally

Install Hugo 0.170 or later (on Windows: `winget install Hugo.Hugo.Extended`), then from the repository root:

```bash
hugo server -D
```

Open <http://localhost:1313>. Changes reload automatically. `-D` includes draft posts.

## Deployment

Every push to `main` builds the site and publishes it through `.github/workflows/deploy.yml`.
