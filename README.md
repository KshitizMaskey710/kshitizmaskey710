# Kshitiz Maskey Jekyll theme

A standalone, lightweight Jekyll conversion of the React/Tailwind references in `../examples/`. It ships plain HTML, Liquid, and CSS; React and Tailwind are not runtime dependencies.

## Run locally

```sh
bundle install
bundle exec jekyll serve --livereload
```

Open `http://127.0.0.1:4000/`.

## Reusing a design

Copy a file from `_templates/` into the site root or `_posts/`, rename it, and replace its front matter and sample content. Layouts own page chrome; `_includes/` contains reusable hero, metadata, card-grid, callout, visual-panel, and related-link components.

Article images referenced by the React examples were not copied because their source files are absent. Add approved images to `assets/images/` and set an `image` front matter value when available.
