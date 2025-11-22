# EEG: Sources (LORETA/eLORETA) + Directed Connectivity (Brainstorm PTE/dPTE)

**Goal:** Localize sources with (e)LORETA and estimate directed connectivity (PTE/dPTE) between ROIs in a compact EEG dataset.

---

## Snapshot
- **Dataset:** small EEG task or resting subset (tutorial-level)
- **Local subset:** <N subjects> · **Disk:** small (hundreds of MB–~1 GB)
- **Tools:** LORETA/eLORETA, Brainstorm (PTE/dPTE)
- **Status:** <planned / in progress / complete>
- **Last updated:** <YYYY-MM-DD>

---

## Data
- **Source:** <dataset link> (public).  
- **What I downloaded:** subjects/sessions; montage info.  
- **Layout:** per-subject folders.

---

## Pipeline (high-level)
1) Preprocess (as in ERP project)  
2) Source imaging: LORETA/eLORETA on averaged data  
3) Connectivity: Brainstorm PTE/dPTE between chosen ROIs  
4) Summarize directionality patterns

---

## Results (to be filled)
- Figure: source maps (peak snapshots)  
- Figure: directed connectivity graph (PTE/dPTE)

---

## Reproducibility
- Versions in `env/TOOL_VERSIONS.md`.  
- Steps: “Preprocess → sources → PTE/dPTE → figures.”  
- Limitations: choice of inverse/ROIs affects results.

---

**Author:** Rene Andrade Rey · 🧪 ORCID: https://orcid.org/0000-0001-5627-579X · 🌐 Scholar: https://scholar.google.es/citations?hl=es&user=Nl3ApFEAAAAJ
