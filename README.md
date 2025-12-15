# Explainable Machine Learning for Predicting Aspiration Pneumonia in Oral Cavity Cancer

### 📄 Published in *Radiotherapy and Oncology* (Impact Factor: 5.3)
**🔗 Official Full Text:** [Read on The Green Journal](https://www.thegreenjournal.com/article/S0167-8140(25)04570-0/abstract)

---

### 📝 Abstract

**Background and purpose**
Aspiration pneumonia is a severe late event that occurs following radiotherapy for oral cavity cancer (OCC). This study aimed to develop explainable machine learning models to predict aspiration pneumonia.

**Materials and methods**
This study included 880 patients with OCC (derivation cohort, 561 patients; external validation cohort, 319 patients) who underwent surgery and adjuvant radiotherapy between 2010 and 2020. Random Forest (RF), eXtreme Gradient Boosting (XGBoost), and Categorical Boosting (CatBoost) models were trained to predict aspiration pneumonia using clinical and dosimetric features. Model performance was evaluated using the area under the curve (AUC). The SHapley Additive exPlanations (SHAP) method was applied to rank feature importance and explain the model.

**Results**
The RF model achieved the highest AUC compared with the XGBoost and CatBoost models in the external validation set (0.966, 0.962, and 0.955, respectively). An explainable RF model identified the mean doses to the superior pharyngeal constrictor muscle (PCM), middle PCM, and supraglottic larynx as the three most important features for predicting aspiration pneumonia in the training and validation sets. The dose–toxicity relationship between the mean dose to the swallowing structures and aspiration pneumonia was nonlinear. The threshold mean dose to the swallowing structures for lowering the risk of aspiration pneumonia was determined. The SHAP force plot provided an individualized interpretation of the model predictions for each patient.

**Conclusion**
An explainable machine learning model can assist clinicians in predicting aspiration pneumonia after radiotherapy for OCC. Individualized predictions may help tailor radiotherapy to reduce the risk of aspiration pneumonia.

---

### 🏆 Key Highlights
- **Role:** First Author
- **Methodology:** Implemented **Random Forest**, **XGBoost**, and **CatBoost** for risk prediction.
- **Explainability:** Utilized **SHAP (SHapley Additive exPlanations)** to interpret model decisions and identify key clinical risk factors.
- **Performance:** The Random Forest model demonstrated superior performance in the external validation set (**AUC = 0.966**).

---

### 💡 Citation
If you find this research helpful, please cite our paper:

> [1] Wu YF, Lin JB, Chen YJ, Leu YS, Sun FJ, Lee J. Explainable machine learning for predicting aspiration pneumonia after radiotherapy in oral cavity cancer. Radiotherapy and Oncology 2025;211:111066.

---

### 📮 Data & Code Availability
The datasets and source code generated during the current study are not publicly available due to intellectual property regulations of the laboratory.

For collaboration inquiries or technical details, please contact the **Corresponding Author**:

**Dr. Jie Lee (李杰 醫師)**
Department of Radiation Oncology, MacKay Memorial Hospital
📧 Email: [sinus.5706@mmh.org.tw](mailto:sinus.5706@mmh.org.tw)
