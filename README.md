# Gene expression divergence of paralogs across celltypes and tissues

Analysis for investigating how different confounders influence
expression divergence of paralog pairs across cell types and tissues in *Zea mays*
using single-cell RNA-seq data.

SingleCell data for *Zea mays* was obtained from the ScPlantDb.

---

## Overview

### Chapter 1 — Data acquisition and preprocessing
Download and preprocess *Z. mays* scRNA-seq datasets from scPlantDB. Includes
data exploration and normalisation. Pseudobulk logcounts by cell type and tissue.

### Chapter 2 — Duplication data integration
Integrate paralog pair annotations and duplication mode classifications from
doubletroubledb. Handles genome annotation version conversion and
filters to nuclear protein-coding genes.

### Chapter 3 — Gene-level analysis
Compute mean expression levels and expression breadth per gene per duplication
mode. Includes Kruskal-Wallis / Dunn's tests and overrepresentation analysis.

### Chapter 4 — Expression divergence
Construct metacells, compute pairwise Spearman correlations
for paralog pairs, and compare correlation distributions across duplication modes
and WGD age classes. Analyse influence of gene function on gene expression correlations.

### Chapter 5 — Gene coexpression network (GCN) inference
Infer a signed hybrid GCN, identify hub genes, and test overrepresentation by duplication mode.

### Chapter 6 — Divergence class classification
Classify paralog pairs into asymmetric divergence, symmetric divergence, or redundancy based on relative expression breadth (REB). Perform ORA per duplication mode.

---
