# CCLE exploratory data analysis

- `CCLE_correlation.Rmd` - Correlation CCLE analysis. Select one gene, get all genes best correlated (and anticorrelated) with it. In all cells, or in a cell/tissue-specific subset. An option to perform KEGG enrichment analysis on the cutoff-selected best correlated and anticorrelated genes.

# Data source

Currently used: `CCLE_DepMap_18Q1_RNAseq_RPKM_20180214.gct` from https://portals.broadinstitute.org/ccle/data

From https://ocg.cancer.gov/programs/ctd2/data-portal, ftp://caftpd.nci.nih.gov/pub/OCG-DCC/CTD2/TGen/CCLE_RNA-seq_Analysis/

From https://docs.google.com/spreadsheets/d/1Ih64DDS5mqDlYFzDyCY9HAUnxvI1b6hapKP_akFuNPY/edit#gid=27255898, http://s3.amazonaws.com/multiassayexperiments/example/ccleMAEO.rds

# Related resources

- R scripts and tutorial for working with CCLE data, RPKM expression and cell annotations, by Kevin Blighe. https://github.com/kevinblighe/AunerLab_CCLE