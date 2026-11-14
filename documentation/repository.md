# Kidney-Genetics repository details

Moved from the top-level README.

## Overview and Methods

The Kidney-Genetics Atlas contains information for about 3.000 kidney-associated genes. This information was gathered from various reliable sources, such as Genomics England PanelApp, PanelApp Australia, PubTator, OMIM, Orphanet, clinical diagnostic panels, and comprehensive literature review.


## Usage

The Kidney-Genetics Atlas is publicly available and accessible through GitHub. Furthermore, the database is automatically and regularly updated to ensure its currency and relevance.
The documentation also shows the current result from each analysis and the merged list of genes as filterable data tables.


## File structure

The repository has the following structure:

```
.
├── analyses/
│   ├── 01_PanelApp/
│   │   ├── data/
│   │   ├── results/
│   │   └── 01_PanelApp.R
│   ├── 02_Literature/
│   │   ├── data/
│   │   ├── results/
│   │   └── 02_Literature.R
│   ├── 03_DiagnosticPanels/
│   │   ├── data/
│   │   ├── results/
│   │   └── 03_DiagnosticPanels.R
│   ├── 04_HPO/
│   │   ├── data/
│   │   ├── results/
│   │   └── 04_HPO.R
│   ├── 05_PubTator/
│   │   ├── data/
│   │   ├── results/
│   │   └── 05_PubTator.R
│   ├── A_MergeAnalysesSources/
│   │   ├── data/
│   │   ├── results/
│   │   └── A_MergeAnalysesSources.R
│   ├── B_AnnotationHGNC/
│   │   ├── data/
│   │   ├── results/
│   │   └── B_AnnotationHGNC.R
│   └── AnnotateMergedTable.R
└── functions/
    ├── blueprintgenetics-functions.R
    ├── hgnc-functions.R
    ├── hpo-functions.R
    ├── natera-functions.R
    ├── NCBI-datasets-v2-API-functions.R
    ├── phantomjs-functions.R
    └── PubTator-functions.R
```

- The `analyses/` directory contains the R scripts for different analyses.
- The `functions/` directory contains the necessary functions for HGNC processing.
- The `data/` sub-directory in each analysis folder stores the input data files, including the publication-specific files and the curated overview Excel table.
- The `results/` sub-directory in each analysis folder stores the generated results.


## Creators and contributors

**Bernt Popp**

- <https://twitter.com/berntpopp>
- <https://github.com/berntpopp>
- <https://orcid.org/0000-0002-3679-1081>
- <https://scholar.google.com/citations?user=Uvhu3t0AAAAJ>

**Constantin Aaron Wolff**

- <https://github.com/ConstantinWolff>
- <https://orcid.org/0000-0002-3277-4559>

**Nina Rank**

- <https://github.com/ninarank>
- <https://orcid.org/0000-0002-5984-4836>

**Jan Halbritter**

- <https://orcid.org/0000-0002-1377-9880>
- <https://scholar.google.com/citations?user=Jt1S5fkAAAAJ>

## Contact

If you have any questions, suggestions, or feedback, please open an issue at <https://github.com/kidney-genetics-org/kidney-genetics-v1/issues>.
