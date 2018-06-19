# Application_Sequencing

This code was written in the Jupyter notebook, and in python
The file code which has the relevant FINAL DRAFT is StanApp.ipynb 

Script for obtaining interview for the Sequencing summer job application
This script accomplishes the task of:
1) Produce a file containing one row for each cell barcode which has >0 count for at least one gene of interest
, and show the cell barcode, and the total count (summed for all genes)
2) Produce a file containing one row for each gene of interest which is expressed in at least one cell
, and show the gene, and the total number of cells in which it is expressed.

Given Files:
Matrix files:  M44_matrix.mtx, M44_genes.tsv, M44_barcodes.tsv
Genes of interest:  365_EMT_gene_signatures.txt
