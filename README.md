# Bioinformatics ML Lab (GEO microarray & yeast cell-cycle)

This project explores public gene expression datasets (e.g., GSE2034, Spellman et al.) with the following steps:
- Standardize gene expression matrices
- Compute correlation-based distances
- Perform hierarchical clustering (Ward linkage)
- Explore cluster stability via bootstrap resampling
- Do pathway enrichment analysis (per-cluster)
- Summarize biological functions & limitations (batch effects, high dimensionality)

## Project layout
```
bio-ml-lab/
  data/
    raw/          # untouched downloads
      GEO/        # GEO cache
    processed/    # cleaned, matrices, annotations
    external/     # pathway resources if needed
  notebooks/
    01_data_download.ipynb
  src/            # python modules, utils
  reports/        # figures, tables, notes
  environment.yml # conda environment
```
