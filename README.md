# 🩺 Breast Cancer Diagnostic Classification

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange.svg)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-red.svg)
![Accuracy](https://img.shields.io/badge/Accuracy-98.25%25-brightgreen.svg)

Predictive machine learning pipeline for binary classification of breast cancer tumors (Malignant vs. Benign) using patient diagnostic feature sets.

---

## 🎯 Overview & Problem Formulation

Breast cancer represents one of the most diagnosed cancers worldwide. Early detection via automated computational diagnostics significantly improves treatment prognosis. This project builds a reliable diagnostic classification pipeline that minimizes false negatives.

---

## 🔬 Exploratory Data Analysis (EDA)

* Detailed feature distribution across tumor geometry (radius, texture, perimeter, area, smoothness, compactness, concavity).
* Correlation analysis identifying high-influence biomarkers separating malignant and benign cases.
* Outlier detection and feature scaling.

---

## 🤖 Models & Benchmark Performance

Three classification models were trained and benchmarked:
1. **K-Nearest Neighbors (KNN)**
2. **Logistic Regression** (Optimized baseline)
3. **XGBoost Classifier**

### 📊 Evaluation Metrics:
| Metric | Score | Note |
|---|---|---|
| **Accuracy** | **98.25%** | High overall diagnostic reliability |
| **Precision** | **1.00** | Zero false positive diagnoses |
| **Recall (Sensitivity)** | **95.83%** | Critical metric for clinical oncology screening |
| **F1-Score** | **97.87%** | Balanced harmonic mean |
| **Jaccard Score** | **0.9583** | High overlap agreement |

### 🔍 Confusion Matrix:
* **True Negatives (Benign correctly identified):** 66
* **False Positives:** 0
* **False Negatives:** 2
* **True Malignants:** 42

---

## 🛠 Tech Stack

* **Language:** Python
* **Machine Learning:** Scikit-learn, XGBoost
* **Data Manipulation & Visualization:** Pandas, NumPy, Matplotlib, Seaborn

---

## 📬 Contact

* **LinkedIn:** [Kuvonchbek Begimkulov](https://linkedin.com/in/kuvonchbek-begimkulov)
* **Email:** [begimqulovquvonchbek53@gmail.com](mailto:begimqulovquvonchbek53@gmail.com)
