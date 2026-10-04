# SatMapKit website

The SatMapKit landing page, tool catalog, and About page. Jekyll builds the site using local layouts and CSS; no remote theme or JavaScript is needed.

## Local preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve --host 127.0.0.1
```

Open <http://127.0.0.1:4000>. The Gemfile pins Jekyll to the version used by GitHub Pages. Keep the generated `_site/` directory out of version control.

## Content

- `index.html` is the only homepage source.
- `_data/tools.yml` contains the project descriptions and card destinations. Each card is a single link, with no separate button.
- `_data/navigation.yml` defines the main navigation.
- `_pages/` contains the About, tool catalog, and 404 pages.
- `_layouts/`, `_includes/`, and `assets/css/site.css` define the presentation.
- `assets/images/slaPanama.png` is the existing scientific figure used on the homepage. Preserve the figure's colors and avoid adding a quantitative caption without checking its source data.

## Publishing

GitHub Pages is configured to publish from the root of `working-version`. This iteration is based on that branch and consolidates its competing homepage sources. Changes made only on `master` do not update the live site. Publish reviewed changes by integrating them into `working-version`, or deliberately change the Pages source as part of a separately authorized deployment.
