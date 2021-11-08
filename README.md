# Ubiq Docs
<a href="https://github.com/ubiq/docs/actions"><img
    src="https://github.com/ubiq/docs/workflows/ci/badge.svg?branch=master"
    alt="CI"
  /></a>

URL: https://docs.ubiqsmart.com/

* Technical documention managed through Git.
* May have non-technical resources as well but [Odin](https://odin.ubiqsmart.com/) is the prefered location.
* Auto-published through continuous integration GitHub Actions.

Uses [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/). Refer to the [Installation guide](https://squidfunk.github.io/mkdocs-material/getting-started/) for more information.

## Commands

* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

```
mkdocs.yml    # The configuration file.
docs/
    index.md  # The documentation homepage.
    ...       # Other markdown pages, images and other files.
```
