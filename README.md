# Elshan Garashli Homepage

This is a simple academic homepage built with [Quarto](https://quarto.org/).

## Structure

- `index.qmd`, `research.qmd`, and `teaching.qmd` are the site pages.
- `assets/` contains public files used by the site, including the profile photo and CV PDF.
- `_quarto.yml` configures the site and navigation.
- `styles.css` contains custom styling.

## Local Preview

Preview the site locally:

```bash
quarto preview
```

Render the site locally:

```bash
quarto render
```

The rendered website is written to `docs/`.

## Publishing

Commit changes and push to `main`. GitHub Actions renders the site and publishes it with GitHub Pages.

The `CNAME` file configures the custom domain:

```text
elshangarashli.com
```

