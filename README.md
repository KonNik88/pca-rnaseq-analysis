# PCA and UMAP analysis of RNA-seq datasets

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)]()
[![scikit-learn](https://img.shields.io/badge/sklearn-PCA-yellow.svg)](https://scikit-learn.org/)
[![scanpy](https://img.shields.io/badge/Scanpy-UMAP-green.svg)](https://scanpy.readthedocs.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A simple analysis of bulk RNA-seq and scRNA-seq datasets using PCA and UMAP.  
The project focuses on QC, visualization, clustering, and interpretation of biological replicates and groups.

## Datasets
- **Bulk RNA-seq**: HL-60 cell line — [GSE184891](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE184891)
- **scRNA-seq**: AML patient samples — [GSE116256](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE116256)

## Goals
- Perform QC analysis on bulk RNA-seq data using PCA
- Check consistency of biological replicates
- Cluster scRNA-seq data using UMAP
- Identify differences between cell groups

## Methods
- PCA via `scikit-learn`
- UMAP and clustering via `scanpy`
- Visualization using `matplotlib` and `seaborn`

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Launch the notebook:
   ```bash
   jupyter notebook Practice_PCA_bulk_RNA_seq_scRNA_seq.ipynb
   ```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
