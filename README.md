# DHEA Transcriptomics Analysis

## Overview

Python-based analysis of RNA-seq differential expression data from Arabidopsis thaliana subjected to steroid hormone treatments and fungal infection.

Treatments analyzed include:
- DHEA
- Testosterone
- Progesterone
- Androstenedione
- 17-hydroxyprogesterone
- Alternaria infection
- Alternaria infection + DHEA

## Analysis workflow

1. Import differential expression results
2. Map genes to GO and GO-Slim annotations
3. Separate upregulated and downregulated genes
4. Quantify GO-term enrichment patterns
5. Generate functional bubble plots
6. Compare treatment-specific and shared responses using Venn diagrams

## Tools

- Python
- Pandas
- Matplotlib
- Seaborn
