# <Project Title>: <Modality & Tools> on <Dataset>

### What this project asks (2–3 lines)
A crisp statement of the scientific question and why it matters.

---

## Data
- **Source:** <dataset name + link> · **License/DUA:** <text>
- **Subset used:** <n subjects/sessions> · **Approx disk:** <X GB> (raw) / <Y GB> (derivatives)
- **Layout:** BIDS (if applicable)

> We **do not** commit raw data to the repository. If needed, link to the public source and keep large artifacts out of git. (GitHub looks for an entry file in `/docs` such as `index.md` when you publish Pages from that folder.)

---

## Pipeline (high-level)
Preprocessing → Analysis → Statistics → QC  
Tools: FreeSurfer / FSL / SPM + CAT12 / Brainstorm / EEGLAB / FieldTrip / BRAPH / MATLAB

Confounds handled (examples): motion, age/sex, site.

---

## Results
- 2–3 key figures (see `results/figures/`)
- Report thresholds (e.g., FWE/FDR; cluster-permutation for M/EEG) and effect sizes.

---

## Reproducibility
- **Versions:** see `env/TOOL_VERSIONS.md`
- **Steps to re-run:** bullet list of actions (no raw data)
- **Known limits:** sample size, heterogeneity, compute

---

## Cite this work
A `CITATION.cff` is included—GitHub renders a “Cite this repository” box automatically.  
When you cut a Release and connect to Zenodo, add the DOI badge here.

---

### Author & links
**Rene Andrade Rey** · 🧪 ORCID: https://orcid.org/0000-0001-5627-579X · 🌐 Google Scholar: https://scholar.google.es/citations?hl=es&user=Nl3ApFEAAAAJ
