<p align="center">
    <img src="documentation/static/img/logo/kidney-genetics_logo.png" alt="Kidney-Genetics logo" width="192" height="192">
</p>

# Kidney-Genetics v1

[![Docs](https://github.com/kidney-genetics-org/kidney-genetics-v1/actions/workflows/gh-pages.yml/badge.svg)](https://github.com/kidney-genetics-org/kidney-genetics-v1/actions/workflows/gh-pages.yml)
[![Documentation site](https://img.shields.io/badge/docs-kidney--genetics--org.github.io-blue)](https://kidney-genetics-org.github.io/kidney-genetics-v1/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Kidney-Genetics is a systematically curated, reproducible list of kidney-related
genes. It compiles about 3,000 kidney-associated genes from Genomics England
PanelApp, PanelApp Australia, PubTator, OMIM, Orphanet, clinical diagnostic
panels, and literature review. R analysis scripts merge and annotate these
sources, and the bookdown documentation presents the resulting gene tables.

This repository holds the original R pipeline (v1). Research use only.

## Quick start

```bash
git clone https://github.com/kidney-genetics-org/kidney-genetics-v1
cd kidney-genetics-v1/
```

Each analysis is an R script under [`analyses/`](analyses/); the README in each
analysis folder lists its prerequisites, configuration, and usage. To build the
documentation locally, see [documentation/README.md](documentation/README.md).

## Documentation

- [The Kidney-Genetics Documentation](https://kidney-genetics-org.github.io/kidney-genetics-v1/)
  (bookdown, built from [`documentation/`](documentation/) by the
  [GitHub Pages workflow](.github/workflows/gh-pages.yml))
- [Repository details](documentation/repository.md): overview, file structure,
  creators and contributors, contact
- [Analyses](analyses/README.md)
- Related: [kidney-genetics-db](https://github.com/kidney-genetics-org/kidney-genetics-db),
  (current Kidney-Genetics database)

## Citing

Use [CITATION.cff](CITATION.cff) for the repository's citation metadata. Until an
archived release is available, include the full Git commit SHA of the database
and analysis scripts used alongside the repository URL in your citation.

No release version or Zenodo DOI is assigned yet. Maintainers can follow
[RELEASING.md](RELEASING.md) to prepare the first release, archive it with Zenodo,
and then add its DOI badge here. Cite the version-specific DOI for reproducibility
once that release is archived.

## License

MIT; see [LICENSE](LICENSE).
