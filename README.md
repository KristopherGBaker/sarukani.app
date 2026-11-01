# sarukani.app

The website for [Sarukani](https://sarukani.app/), a WaniKani client for iPhone and iPad.

It is an [Inkwell](https://github.com/KristopherGBaker/inkwell) project. The theme in `themes/sarukani/` and the copy in
`data/*.yml` are exported by Silverpoint from `docs/design/site/sarukani-site.silverpoint` in the Sarukani repository,
which links the app's design system (`docs/design/sarukani-design-system.silverpoint`). Change the design there and
export again; edit the copy in `data/` or the pages in `content/pages/` directly.

- `inkwell build` writes the site to `public/`; `inkwell serve` previews it.
- Pushing to `main` deploys to GitHub Pages (`.github/workflows/pages.yml`).
- `themes/sarukani/templates/base.html` is hand-edited to load Inter and Zen Old Mincho from Google Fonts, because
  Silverpoint's export does not carry fonts yet; a re-export keeps it rather than replacing it.
- `content/pages/privacy.md` is the privacy policy at `/privacy/`, the URL App Store Connect lists. Its source of truth is
  `docs/PRIVACY.md` in the Sarukani repository: change both together.
