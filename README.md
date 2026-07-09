# Elshan Garashli Homepage

This is a simple academic homepage built with [Quarto](https://quarto.org/).

## Local Preview

Install Quarto, then run:

```bash
quarto preview
```

To render the site locally:

```bash
quarto render
```

The rendered website is written to `docs/`.

## Publishing with GitHub Pages

This repository includes a GitHub Actions workflow at `.github/workflows/publish.yml`.

After pushing the repository to GitHub:

1. Open the repository settings on GitHub.
2. Go to `Pages`.
3. Set the source to `GitHub Actions`.
4. Push to the `main` branch, or run the workflow manually.

The `CNAME` file configures the custom domain:

```text
elshangarashli.com
```

At the domain registrar, point the domain to GitHub Pages using GitHub's recommended DNS records.

