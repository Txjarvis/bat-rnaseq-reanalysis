# Bat RNA-seq Reanalysis

A beginner-friendly bioinformatics reanalysis project exploring how infection and temperature influence gene expression in bats using RNA-seq data.

---

## Project Overview

This project reanalyses publicly available RNA-seq count data to investigate transcriptional responses under different experimental conditions. The workflow focuses on differential expression analysis, interaction modelling, visualisation, and functional interpretation.

The main biological question explored is:

> How do temperature and infection status affect bat gene expression, and are there genes whose response depends on the interaction between both factors?

---

## Dataset

Public RNA-seq data were obtained from GEO:

- GSE256068

Raw sequencing files are not included in this repository due to file size limitations.

---

## Analysis Workflow

The project was performed in R using a reproducible notebook-based workflow.

### Steps

1. Import count matrix and sample metadata
2. Perform quality control and PCA
3. Run differential expression analysis using DESeq2
4. Investigate interaction effects between temperature and infection
5. Generate visualisations including:
   - PCA plots
   - Volcano plots
   - Heatmaps
6. Perform functional enrichment analysis
7. Replicate and explore key findings from the original study

---

## Repository Structure

```text
bat-rnaseq-reanalysis/
├── notebooks/
├── figures/
├── results/
├── data/
├── README.md
└── .gitignore

## Example Outputs

The analysis includes:
Principal Component Analysis (PCA)
Differential expression volcano plots
Heatmaps of significant genes
Interaction effect analyses
Functional enrichment results

Tegan Jarvis
MSc Bioinformatics
