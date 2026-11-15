# Kiyoyozi website

Website for **Kiyoyozi – The Air Quality Lab** at Ifakara Health Institute. Built with [Quarto](https://quarto.org), deployed to GitHub Pages.

## Edit

| File | What it holds |
|---|---|
| `index.qmd` | Home page |
| `data.qmd` | Open data specification |
| `about.qmd` | About the lab |
| `_quarto.yml` | Site settings, navigation, footer |
| `assets/kiyoyozi.scss` | Colours, fonts, layout |
| `assets/logo.svg` | Logo and favicon |

Preview locally with live reload:

```sh
quarto preview
```

## Deploy

Every push to `main` renders the site and publishes it via `.github/workflows/publish.yml`.

One-time setup: in the repository, go to **Settings > Pages > Build and deployment** and set **Source** to **GitHub Actions**.

The site is at <https://kiyoyozi.github.io/>, which GitHub serves from this repository because it is named `kiyoyozi.github.io`. If you add a custom domain, update `site-url` in `_quarto.yml`.
