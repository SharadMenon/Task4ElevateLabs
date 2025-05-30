# 🔍 Logistic Regression Binary Classifier with Threshold Tuning and ROC Analysis

This project demonstrates a complete binary classification pipeline using **Logistic Regression**, with a focus on evaluating and improving model performance using ROC-AUC and custom threshold tuning.

---

## 📁 Project Overview

This task includes:

1. **Binary Classification Dataset** – Breast Cancer dataset from `sklearn.datasets`
2. **Data Preprocessing** – Train-test split and feature standardization
3. **Model Training** – Logistic Regression
4. **Evaluation Metrics**:
   - Confusion Matrix
   - Precision, Recall, Accuracy
   - ROC Curve and AUC Score
5. **Threshold Tuning** – Custom classification thresholds
6. **Sigmoid Function** – Visualization to understand probability output

---

## 📊 Dataset

We use the dataset **Breast Cancer Wisconsin** dataset from Kaggle
---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Scikit-learn (`sklearn`)
- NumPy & Pandas

---

## 🧪 Evaluation Metrics

- **Accuracy**: Overall correctness
- **Precision**: How many predicted positives were actually positive?
- **Recall (Sensitivity)**: How many actual positives were correctly predicted?
- **ROC-AUC**: Area under the ROC curve, summarizes performance across all thresholds

---

## 🔧 Custom Threshold Tuning

We analyze how adjusting the classification **threshold** (instead of the default 0.5) impacts precision and recall.

