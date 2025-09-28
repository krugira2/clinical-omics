# Clinical & Omics Data Analysis Projects

## Overview
This repository contains two complementary projects aimed at pharma/biotech analyst roles. Together, they show you can work with both **clinical datasets** (patient-level) and **omics-style data** (high-dimensional).

- **Project 1 — Clinical EDA (UCI Heart Disease, Cleveland)**
- **Project 2 — Omics PCA (Gene Expression–like, Breast Cancer dataset)**

---

## Project 1 — Clinical EDA (UCI Heart Disease, Cleveland)

**Summary**
- Rows: 303, Cols: 14  
- Class balance (disease = 1): 45.87%  
- Baseline logistic regression  
  - Accuracy: 0.868  
  - ROC-AUC: 0.931

**Artifacts**
- `reports/clinical_age_hist.png`  
- `reports/clinical_chol_by_disease.png`  
- `reports/clinical_cp_vs_disease.png`

**Notebook**
- `notebooks/01_clinical_heart_disease.ipynb`

**What this shows**
- Clinical data cleaning (missing values, numeric conversions)
- Exploratory analysis and medical feature understanding
- Quick baseline modeling for a clinical outcome

---

## Project 2 — Omics PCA (Gene Expression–like, Breast Cancer dataset)

**Summary**
- Samples: 569, Features: 30  
- PCA variance explained: PC1 = 44.3%, PC2 = 19.0%  
- k-means clustering silhouette score: 0.343

**Artifacts**
- `reports/omics_pca.png`  
- `reports/omics_pca_scores.csv`

**Notebook**
- `notebooks/02_omics_gene_expression.ipynb`

**What this shows**
- High-dimensional data handling
- Dimensionality reduction (PCA) and visualization
- Unsupervised learning (k-means) + validation (silhouette)

---

## Environment

- Python 3.11  
- Packages: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `ucimlrepo`

To recreate a simple environment:
```bash
pip install pandas numpy matplotlib scikit-learn ucimlrepo

