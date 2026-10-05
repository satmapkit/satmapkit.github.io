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
- `assets/images/nasa-grantee.png` is the [official NASA grantee insignia](https://www.nasa.gov/wp-content/uploads/2023/07/nasa-granteeinsignia-rgb.png). The About page follows [NASA's grantee guidelines](https://www.nasa.gov/wp-content/uploads/2018/03/nasa_insignia_guidelines_for_nasa_grantees.pdf), including protected space, a contrasting border, and the required disclaimer beside or below the logo in the funding credits. Its use is limited to the active grant's work on a website produced or controlled by the grant recipient.

## Publishing

GitHub Pages publishes from the root of `master`, the repository's default branch. Push reviewed website changes to `master` to deploy them. The earlier publishing branch, `working-version`, is retained as history; it is no longer the Pages source.
