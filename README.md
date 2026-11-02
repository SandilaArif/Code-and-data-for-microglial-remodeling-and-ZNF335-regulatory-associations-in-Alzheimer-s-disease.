# Conserved lysosome-DAM program coupling and TF-regulator integration in AD microglia

This repository package contains the code, derived source tables, figure assets, and manuscript support files for the manuscript:

**Conserved lysosome-DAM program coupling nominates ZNF335 through TF-regulator integration in Alzheimer's disease microglia**

Package generated: 2026-06-06 20:46:08

## Contents

- `code/analysis/`: analysis and figure-generation scripts used during the project.
- `code/manuscript_formatting/`: scripts used to format the final manuscript/SI and EndNote import files.
- `data/main_figure_source_csvs/`: panel-level CSVs for main figures.
- `data/supplementary_figure_source_csvs/`: panel-level CSVs for supplementary figures.
- `data/robustness_specificity/`: robustness, specificity, leave-one-dataset-out, partial-correlation, and evidence-table CSVs.
- `data/seaad_sensitivity/`: corrected SEA-AD sensitivity tables.
- `data/bayesian_hgt/`: donor-held-out HGT metrics, ablations, uncertainty, calibration, and feature relevance tables.
- `data/external_validation/`: SEA-AD-trained external-validation outputs where available.
- `figures/`: final main and supplementary figure assets.
- `manuscript/`: final Progress in Neurobiology-formatted manuscript and supplementary information.
- `references/`: EndNote/RIS/BibTeX/plain-text reference exports.
- `MANIFEST.csv`: file inventory with SHA-256 checksums.

## Raw data policy

Raw FASTQ files and large processed single-cell objects are **not** included because they are too large for ordinary GitHub hosting and should be obtained from the public repositories listed in `docs/DATA_AVAILABILITY.md`. This package includes derived source tables sufficient to audit the figures, tables, and manuscript-level quantitative claims.

## Recommended repository setup

If large `.h5ad`, `.rds`, `.loom`, matrix, or image files are later added, use Git LFS. The included `.gitignore` excludes common raw/intermediate single-cell formats by default.

## Reproducibility note

The final manuscript emphasizes sample/donor-level inference, corrected SEA-AD sensitivity, detection-aware TF/regulator integration, and donor-held-out HGT validation to avoid cell-level pseudoreplication.
