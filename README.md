# genomic-medicine-portfolio
Single-cell analysis of PBMC immune cells and structural validation of drug target IL-32
# Single-Cell Genomic Analysis & Drug Target Identification

## Project Overview
This project simulates a computational biology workflow. It processes single-cell RNA sequencing (scRNA-seq) data to identify immune cell populations and analyses potential drug targets using structural biology tools.

## Key Workflows
1.  **Genomic Pipeline:**
    * Processed 2,700 human PBMC cells using **Scanpy**.
    * Performed QC, Normalization, and Dimensionality Reduction (PCA).
    * Clustered cells using the **Leiden algorithm**.
2.  **Biological Insight:**
    * Identified **CD4+ T-Cells** via marker genes (*LTB, IL32*).
    * Performed Differential Expression analysis to validate *IL32* as a specific target.
3.  **Structural Analysis:**
    * Retrieved the 3D crystal structure of IL-32 (PDB: 2R3C) using **Biopython**.
    * Analyzed atomic coordinates to map the protein's center of mass for potential ligand binding studies.

## Technologies Used
* **Python:** Pandas, NumPy
* **Bioinformatics:** Scanpy, Biopython
* **Visualization:** Matplotlib, Seaborn

## Data Source
* 10x Genomics (PBMC 3k dataset)
* RCSB Protein Data Bank (2R3C)

## Acknowledgements
* Data provided by **10x Genomics**.
* Workflow references: **Scanpy Documentation**.
* AI tool assistantance for improving workflow and debugging
