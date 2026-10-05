# alex-petrenko.github.io

Personal website, built with [al-folio](https://github.com/alshedivat/al-folio) (Jekyll).

Where things live:

- `_pages/`: home (`about.md`), publications, projects, repositories, CV, personal pages
- `_bibliography/papers.bib`: publications (rendered by jekyll-scholar)
- `_projects/`, `_news/`: project cards and news items
- `_data/socials.yml`, `_data/coauthors.yml`, `_data/venues.yml`: links
- `assets/cv.pdf`: CV (copied from the LaTeX CV repo)

Local preview:

```sh
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

Deploy: pushing to `master` runs `.github/workflows/deploy.yml`, which builds the site into the `gh-pages` branch.
GitHub Pages must be set to serve from `gh-pages` (Settings → Pages).
