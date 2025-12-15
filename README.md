# Explainable Machine Learning for Predicting Aspiration Pneumonia in Oral Cavity Cancer

### 📄 Published in *Radiotherapy and Oncology* (Impact Factor: 5.3)
**Paper Title:** Explainable machine learning for predicting aspiration pneumonia after radiotherapy in oral cavity cancer  
**Ranking:** 22/212 (Radiology, Nuclear Medicine & Medical Imaging), PR 89.9

---

## Project Overview
This project aims to predict the risk of aspiration pneumonia in oral cavity cancer patients after radiotherapy using machine learning models. We utilized **SHAP (SHapley Additive exPlanations)** to provide interpretability for the clinical decision-making process.

### Methods
- **Models Compared:** Random Forest (RF), XGBoost, CatBoost.
- **Best Model:** **Random Forest (RF)** achieved the best performance in both internal and external validation (evaluated by AUC and F1-score).
- **Explainability:** SHAP summary plots and dependence plots were generated to visualize key risk factors.

### Repository Structure
- `code/`: Python scripts for data preprocessing, model training, and SHAP analysis.
- `SHAP_img/`: Visualization results (Summary plots, Force plots).
- `FinalPaper/`: The manuscript and supplementary materials.

---

### Key Results
The Random Forest model successfully identified high-risk patients, helping clinicians intervene earlier to prevent aspiration pneumonia.

---
**Author:** Yu-Fan Wu (First Author)
**Affiliation:** Fu Jen Catholic University / National Yang Ming Chiao Tung University
