## Phertilizer: growing a clonal tree from ultra-low coverage single-cell DNA sequencing data of tumors
This is the accompanyinying data repository. The Phertilizer code repostiory is located at https://github.com/elkebir-group/phertilizer.


![Overview of Phertilizer](overview.png)
Phertilizer infers a clonal tree with SNV and CNA genotypes given ultra-low coverage single-cell sequencing data.
(a) A tumor is composed of groups of cells, or clones with distinct genotypes.
(b) Ultra-low coverage single-cell DNA seequencing produces total read counts and variant read countsfor n cells and m SNV loci, and read-depth ratios for the same cells for an input set of bins.
(c) Phertilizer infers a cell clustering, SNV genotypes, CNA genotypes and a clonal tree  with maximum posterior probability.

## Available Data
1. 10X Genomics Breast Cancer Data from [Zaccaria et al. (2021)](10.1038/s41587-020-0661-6) located in `10x_data`
2. DLP+ Ovarian Cell Lines from [Laks et al. (2019)](https://doi.org/10.1016/j.cell.2019.10.026) located in `DLP_data`
3. Simulation input files located at [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6467844.svg)](https://doi.org/10.5281/zenodo.6467844)
4. Simulation output files located in `simulations/output`
