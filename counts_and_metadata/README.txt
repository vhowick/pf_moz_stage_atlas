Read me file for allcellinfo_pfmca_20200930.csv and counts_pfmca_20200525.csv

counts_pfmca_20200525.csv countains the raw counts from 1467 cells that passed QC.

allcellinfo_pfmca_20200930.csv contains meta data for the 1467 cells that passed QC including experimental information, qc metrics, and results of various analyses. Generally corresponds to File S2 which additionally is formatted with colors and annotation in Excel.

cols 1-19: cell metadata and experimental information including collection stage day postinfectious feed (day), time (for activation experiment), and parasite strain. 

cols 20-28: QC metrics 

col 31: sample accession for ENA

cols 32-33: fig 1 clustering and order of cells in heatmap

col 34: gam sex assignment

col 35-36: ookinete clusters and slingshot pseudotime

col 37: pb pf integration cluster assignment

col 38-40: scmap cell asignment (topcell) with corresponding ShortenedLifeStage2 of that cell and cosine similarity

col 41-42: spz seurat clusters and pseudotime from fig 3

col 43-46: Spearman and Pearson correlation with the top matched bulk transcriptome frome Linder et al (doi: 10.1038/s41467-019-12936-6)

col 47: spz activation seurat clusters (fig 4)

