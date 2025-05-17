# COVID_RNASeq_Analysis
# 🧬 COVID-19 RNA-Seq Analysis

This repository contains a complete end-to-end RNA-Seq analysis workflow comparing **COVID-19 patient samples** to **Healthy controls**. The pipeline includes normalization, dimensionality reduction, differential expression analysis, and functional enrichment.

## 🛠️ Workflow Summary

- ✅ TPM, VST, and Log2CPM normalization
- ✅ Dimensionality reduction using PCA and UMAP
- ✅ Differential expression analysis using DESeq2
- ✅ Volcano plot and heatmap visualization
- ✅ Gene Set Enrichment Analysis (GSEA)

## 📁 Included Files

| File | Description |
|------|-------------|
| `Code.Rmd` | R Markdown notebook for the full analysis |
| `Design.txt` | Sample metadata with group labels |
| `Raw_Read_Count.txt` | Original gene-level read counts |
| `ProtCodingCount.txt` | Filtered protein-coding gene counts |
| `TPM_Count.txt` | TPM-normalized expression values |
| `VST_ProtCodingCount.txt` | VST-normalized data for PCA/heatmaps |
| `Results_Covid_vs_HC.txt` | DESeq2 differential expression output |
| `GSEA_Results.txt` | Pathway enrichment results |
| `VolcanoPlot.pdf` | Visualization of DE genes |
| `Glycolysis_Heatmap.pdf` | Expression of glycolysis genes |
| `GSEA_Barplot.pdf` | Barplot of enriched pathways |

## 🔍 How to Reproduce

1. Clone this repository or download the files.
2. Open `Code.Rmd` in RStudio.
3. Install required R packages (`DESeq2`, `ComplexHeatmap`, `PCAtools`, `enrichR`, etc.)
4. Run each section of the notebook to reproduce figures and results.

## 📊 Results Preview

- Upregulated pathways in COVID: **inflammation, glycolysis**
- Dimensionality reduction shows distinct clustering by group
- DE genes visualized in volcano and heatmap formats

## 🙋 Author

**Preethi Mathari**  
Graduate Student, Molecular Biology & Bioinformatics  
📧 pmathari@mtu.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/preethi-mathari-p-8b3881175)

## 📄 License

This project is for academic and educational purposes only.
