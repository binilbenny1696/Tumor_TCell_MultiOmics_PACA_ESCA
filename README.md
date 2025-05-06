# 🧬 Tumor_TCell_MultiOmics_PACA_ESCA

This project presents a **multi-omics single-cell analysis** of tumor-infiltrating T cells in **pancreatic (PACA)** and **esophageal (ESCA)** cancers using the **GSE156728 dataset**. It integrates transcriptomic data, dimensionality reduction, and functional gene set enrichment to dissect immune heterogeneity in the tumor microenvironment (TME).

---

## 🎯 Objectives

- Identify CD4+, CD8+, Treg, and exhausted T cell clusters using **Seurat**.
- Quantify FOXP3 and IL2RA expression across clusters and cancer types.
- Perform differential expression and GO enrichment analyses.
- Evaluate T cell subtype distributions in **PIK3CA mutant vs wild-type PACA**.

---

## 🧰 Tools Used

| Analysis Type | Tools |
|---------------|-------|
| Clustering & UMAP | Seurat (R), UMAP |
| Marker Detection | `FindAllMarkers`, Wilcoxon test |
| Enrichment Analysis | `clusterProfiler` (GO) |
| Visualization | `ggplot2`, volcano plots, bar charts |

---

## 📁 Project Structure


---

## 🔍 Key Findings

| Subtype | Insight |
|---------|---------|
| Tregs | Cluster 3 with FOXP3, IL2RA, TNFRSF18 expression (5.2x upregulation) |
| CD8+ | Enriched in ESCA tumors; high GZMB, PRF1 |
| Exhausted | Express CTLA4, PDCD1, lower IFNG |
| FOXP3 | Highest in PACA PIK3CA+ samples |
| GO Enrichment | Cytokine signaling, T cell activation, apoptosis |

---

## 📚 Dataset Reference

- **GSE156728**: scRNA-seq of tumor-infiltrating lymphocytes in multiple cancers

---

## 👤 Author

**Binil Benny**  
Immuno-oncology | scRNA-seq | Bioinformatics  
GitHub: [@binilbenny1696](https://github.com/binilbenny1696)

---

