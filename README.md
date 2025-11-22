# EEG — Sources (LORETA/eLORETA) + Directed Connectivity (Brainstorm PTE/dPTE)
[![License](https://img.shields.io/github/license/andraderenew/eeg_sources-connectivity_loreta-brainstorm_pte)](LICENSE)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.XXXXXXX-blue)](#cite-this-work)
[![Pages](https://img.shields.io/website?url=https%3A%2F%2Fandraderenew.github.io%2Feeg_sources-connectivity_loreta-brainstorm_pte%2F)](https://andraderenew.github.io/eeg_sources-connectivity_loreta-brainstorm_pte/)
![Release](https://img.shields.io/github/v/release/andraderenew/eeg_sources-connectivity_loreta-brainstorm_pte?include_prereleases)
![Last commit](https://img.shields.io/github/last-commit/andraderenew/eeg_sources-connectivity_loreta-brainstorm_pte)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0001--5627--579X-A6CE39)](https://orcid.org/0000-0001-5627-579X)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-4285F4)](https://scholar.google.es/citations?hl=es&user=Nl3ApFEAAAAJ)

**One-line:** Localize sources with (e)LORETA and estimate directed connectivity using Brainstorm PTE/dPTE.

## Overview
Source imaging with **LORETA/eLORETA** and **directed connectivity** (**PTE/dPTE** in Brainstorm) on a compact EEG subset.

## Data & subset
See `DATA_SOURCES.md`. Suggested: <5 subjects>; small footprint (hundreds of MB–~1 GB).

## Pipeline
Preproc (as in ERPs) → sources (LORETA/eLORETA) → directed connectivity (PTE/dPTE) between ROIs → figures.

## Results (to be filled)
- Source maps (peaks)  
- Directed connectivity graph (PTE/dPTE)

## Reproducibility
- Versions: see `env/TOOL_VERSIONS.md`  
- Steps: “Preprocess → sources → PTE/dPTE → figures.”  
- Limits: inverse/ROI choices affect results

## Cite this work
See `CITATION.cff` (add DOI after first Release).
