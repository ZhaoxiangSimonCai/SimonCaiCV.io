---
title: Machine learning of cancer type and tissue of origin from proteomes of 1,277 human tissue samples and 975 cancer cell lines
tags:

- Machine learning
- Cancer unknown primary
- Proteomics

date: "2023-10-14T00:00:00Z"

---

Cancer type is determined via assessment of tumour morphology, aided by immunohistochemical staining patterns. The development of machine learning (ML) models using histology slides has powered the image-based prediction of the site of origin in cancer of unknown primary (CUP). Here, we present an ML-based method to predict cancer type from a pan-cancer cohort consisting of 1,289 human tissue samples spanning 44 cancer types and 26 different tissues based on proteomic data. All samples were processed using data-independent acquisition mass spectrometry (DIA-MS).  Two proteomic profiles from the pan-cancer cell line cohort were generated using two different sample preparation methods. These were normalized and merged by averaging the protein abundance, yielding a single training set (D1) with 975 cell lines and 9,688 proteins. Similarly, 1,277 tissue samples were processed by DIA-MS, quantifying 9,501 proteins. We trained a classifier using the cell lines (D1) as the baseline training set, and consecutively added 10% of D2 to D1 for online ML. We tested the baseline model and each subsequent new model on the test set T1. We observed a monotonic performance increase from 0.89 (baseline; Top-1 accuracy) to 0.97 (all D2 were used) when predicting the six cancer types. We observed an analogous trend when predicting the seven tissue types (from 0.64 to 0.84). Our proteomic-based ML model can predict cancer type and carcinoma tissue of origin in concordance with existing histopathological classification. It can also assign multiple probabilities to tumour type and tissue of origin, potentially enabling the classification of challenging pathology cases, such as CUP in future work. By adding tissue samples stepwise to the existing model, its predictive performance can be further enhanced. This reflects a real-world knowledge base that will continue to increase in predictive power with additional incremental proteomic data..