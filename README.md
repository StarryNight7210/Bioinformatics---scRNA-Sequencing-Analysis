# Bioinformatics---scRNA-Sequencing-Analysis
GT Bioinformatics Project #1

Pipeline to sample data from dataset contains Alzheimer's and healthy patients (in order to stay under RAM limit), preprocess, cluster, and use Leiden clusters to determine cell type using external reference to match top 10 marker genes for each cluster to a cell type

Uses Python with ScanPy, Pandas, NumPy, Sci-kit, and Matplotlib 

Findings:

 - Significant changes in oligodendrocyte, microglia and astrocyte marker genes across AD and CT (control/healthy) patients
 - Endothelial and mitochrondrial cells are likely not good indicators
 - For visual representations, using varying principal components is required to ensure all variations between groups are seen

Dataset Link: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE175814

Presentation Link: https://docs.google.com/presentation/d/1LcLx9yly7stEnPzTImVlG45OoZ1Vm5J3-1LTd_RqVIM/edit?usp=sharing
