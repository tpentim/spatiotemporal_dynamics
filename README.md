# Code repository for Lisek*, Theurillat*, Pentimalli* et al 'Spatiotemporal dynamics of tumor microenvironment remodelling' bioRxiv 2025

Raw data can be downloaded from GEO (after publication). The data includes 12 single-nuclei and 12 high-resolution spatial transcriptomics data (Open-ST) from a murine model of triple-negative breast cancer. Tumors have been profiled in 3 biological replicates from 4 timepoints (T0: control, T1-T3: tumor). 3 Open-ST data from xenograft tumor obtained throguh transplantation in immunocompetent mice of tumor cells alone (A), tumor cells + normal fibroblasts (B) and tumor cells + myofibroblasts (C) are also included.

The script data_processing.Rmd describes how to process single-nuclei data (starting from the filtered cellrnager matrices) and Open-ST spatial transcriptomics data (starting from the stitched spacemake matrices).
Pre-processed object can then be used to reproduce the main and supplementary figures using the 'figure_reproducibility.Rmd' script.

Alternatively, pre-processed single-nuclei and spatial objects generated with 'data_processing.Rmd' and the output of 'figure_reproducibility.Rmd' in HTML format can be downloaded directly from Zenodo.
