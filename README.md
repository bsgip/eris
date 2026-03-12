# Eris

Eris is a collection of multi-commodity energy modelling tools.

This repo contains the source for a documentation site, serving as a landing page for Eris and linking through to the individual tools and libraries that make up Eris suite.

---

**Documentation**: [https://bsgip.github.io/eris](https://bsgip.github.io/eris)

---

## Deployment

The documentation is built and deployed automatically by a [GitHub Action](.github/workflows/build-docs.yml) on pushes to `main`.

The documenation is hosted on this GitHub pages site, [https://bsgip.github.io/eris](https://bsgip.github.io/eris).

## Setup

The Eris documentation site is built using [Material for Mkdocs](https://squidfunk.github.io/mkdocs-material/).

In a suitable virtual environment, install `mkdocs-material`,

``` sh
pip install mkdocs-material
```

## Building Locally

Build and serve the site locally with,

``` sh
mkdocs serve
```

This makes the site accessible from [http://127.0.0.1:8000/eris/](http://127.0.0.1:8000/eris/).

If you only want to check the site builds correctly run,

``` sh
mkdocs build
```

## Updating the Site

The site is a collection of [markdown](https://www.markdownguide.org/) files in the [docs/](docs) directory.

The site is configured through the [mkdocs.yml](mkdocs.yml) file.

The following sites might be helpful when updating the site or changing the site's configuration,

- [Material for MkDocs Reference](https://squidfunk.github.io/mkdocs-material/reference/)
- [MkDocs Userguide](https://www.mkdocs.org/user-guide/)



