# Bioinformatics---scRNA-Sequencing-Analysis
GT Bioinformatics Project #1

Pipeline to sample data from dataset contains Alzheimer's and healthy patients (in order to stay under RAM limit), preprocess, cluster, and use Leiden clusters to determine cell type using external reference to match top 10 marker genes for each cluster to a cell type

Uses Python with ScanPy, Pandas, NumPy, Sci-kit, and Matplotlib 

To Run Code:
 - Ensure data-combiner file is run first, it samples the data used for analysis and generates data file used by the other notebook for analysis
 - Data file will be added to main directory in user's Google Drive

Findings:

 - Significant changes in oligodendrocyte, microglia and astrocyte marker genes across AD and CT (control/healthy) patients
 - Endothelial and mitochrondrial cells are likely not good indicators
 - For visual representations, using varying principal components is required to ensure all variations between groups are seen

Dataset Link: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE175814
