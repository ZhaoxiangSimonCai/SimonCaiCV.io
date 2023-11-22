---
title: Machine Learning for multi-omics data integration in cancer

event: Multi-Omics ONLINE Webinar

event_url: https://frontlinegenomics.com/multi-omics-online-july-2022/

location: Virtual

abstract: "Introduction
Proteomic data provide unique insights into the molecular behaviour of cells in both healthy and disease contexts. Proteomics can reveal novel associations between genotype and phenotype, beyond what is apparent from genomics or transcriptomics alone. However, a lack of large proteomic datasets across a range of cancer types has limited our understanding of proteome network organisation and regulation.
Methods
We produced a pan-cancer proteomic map derived from 949 human cancer cell lines, namely ProCan-DepMapSanger. The map encompasses more than 40 cancer types derived from over 28 distinct human tissues. The samples were processed with a clinically-relevant workflow involving rapid and minimally complex sample preparation. The raw proteomic data were acquired by data independent acquisition mass spectrometry (DIA-MS) at ProCan® in Australia. The processed data were analysed with a bespoke deep learning-based pipeline (DeeProM) that integrates multi-omics, drug responses and CRISPR-Cas9 gene essentiality information produced at the Wellcome Sanger Institute.
Preliminary Data
Raw DIA-MS data were processed with DIA-NN and MaxLFQ, quantifying 8,498 proteins. The ProCan-DepMapSanger dataset significantly expands the existing molecular characterizations of this broad range of cancer cell line models. High correlations were observed between replicates of each cell line, yielding a sample-wise median Pearson’s correlation coefficient (Pearson’s r) of 0.92. Correlations between unmatched samples from the same instrument or batch were similar to random (median Pearson’s r = 0.75). We also confirmed that our dataset is consistent with other independent previously published proteomic datasets that comprise smaller subsets of the same cell lines. Nonlinear dimensionality reduction using Uniform Manifold Approximation and Projection (UMAP) showed no evidence of instrument or batch effects. Next, we defined a stringent set of protein quantifications that were supported by measuring more than one peptide (n = 6,692 human proteins). Visualization of these protein intensities via UMAP showed groupings by cell type of origin. Hematopoietic and lymphoid cells showed the most distinct clustering away from other cell types, and these could be further segregated into different cell lineages. This high-level dimensionality reduction suggested a profile of protein expression that relates to cell type of origin. Furthermore, DeeProM enabled the full integration of proteomic data with drug responses and CRISPR-Cas9 gene essentiality screens to build a comprehensive map of protein-specific biomarkers of cancer vulnerabilities that are essential for cancer cell survival and growth. Notably, to the best of our knowledge, this is the first comprehensive demonstration that proteomic data spanning a broad range of cancer cell types and molecular backgrounds have significant utility for predicting cancer cell vulnerabilities.
Novel Aspect
ProCan-DepMapSanger provides a definitive map of cancer dependencies and the deep learning-based method DeeProM enables protein biomarker discovery"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-07-28"
date_end: "2022-07-28"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-02-18T00:00:00Z"

authors: ["Zhaoxiang Cai", "Rebecca C Poulos", "Jia Liu", "Qing Zhong"]
tags: [ "Machine learning", "Multi-omics", "Pan-cancer", "Drug response"]

# Is this a featured talk? (true/false)
featured: false

---
