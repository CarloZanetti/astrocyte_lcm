# Millie LCM Proteomics Analysis

## Project Overview
Analysis of Laser Capture Microdissection (LCM) proteomics samples.
**Run Number:** 01
**Date:** 2026-02-21

## Navigation
- `notebooks/`: Contains the `.qmd` analysis files.
- `docs/`: Rendered HTML website for viewing results.
- `scripts/`: Modular R/Python scripts.
- `data/`: (Not synced to GitHub) Raw and processed data stored at `/camp/home/zanettc/home/shared/zanettc/millie_proteomics/data
`.

## Reproducibility
This project uses `renv`. To restore the environment, run:
```R
renv::restore()

### How to set up the environment
1. Open the project in RStudio or `cd` into this directory in your terminal.
2. If `renv` is not installed on your system, run: `install.packages("renv")`.
3. Run `renv::restore()` to install the exact package versions used in this analysis.
