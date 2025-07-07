# OC-CORS

**Reclassification of Ovarian Cancer Patients Based on Cell-of-Origin Single Cell Gene Expression Signatures**

![OcCORS](https://github.com/user-attachments/assets/082d953d-0728-416e-9cd9-80cbba76a35f)


---

## 🧬 About the Project

**OC-CORS** aims to improve the stratification of ovarian cancer patients by reclassifying them based on gene expression signatures derived from the normal biology of the cell-of-origin. These signatures are inferred using single-cell RNA-seq data, and then applied to bulk patient transcriptomes to identify more biologically meaningful subgroups.

This project uses **Scanpy** to perform:
- Quality control and filtering
- Normalization and log transformation
- Identification of highly variable genes
- Regressing out technical effects
- Dimensionality reduction (PCA, UMAP)
- Clustering (Leiden algorithm)
- Marker gene identification
- Differential expression analysis and export of top markers

---

## 📁 Repository Structure

.
├── OC-CORS_notebook.ipynb # Full Scanpy pipeline with explanations
├── OC-CORS-graphical-abstract.png # Graphical abstract of the project
└── README.md # This file

yaml
Copiar código

---

## 🧪 Dependencies

Make sure you have the following packages installed (e.g. via pip):

```bash
pip install scanpy anndata pandas numpy matplotlib seaborn leidenalg igraph umap-learn
