# 🧬 Breast Cancer Detection

## Overview
This project predicts whether a breast tumor is **malignant or benign** using machine learning models trained on the **Breast Cancer Wisconsin (Diagnostic)** dataset.

Features are extracted from **fine needle aspirate (FNA)** images of cell nuclei, and classification performance is evaluated using standard metrics.

The project was developed using **Jupyter Notebook**.

---

## Dataset
- **Breast Cancer Wisconsin (Diagnostic) Dataset**
- Target variable: `diagnosis`
  - Benign (B → 0)
  - Malignant (M → 1)

Features describe geometric properties of cell nuclei derived from FNA images.

---

## Methodology
- Feature scaling using **StandardScaler**
- Support Vector Machine (**SVM**) classifier
- Model trained on scaled numerical features
- Predictions evaluated on classification performance metrics

---

## Model Performance
- **Accuracy:** 0.9625  
- **Error Rate:** 0.0375  
- **Precision:** 0.9545  
- **Recall:** 0.9130  
- **F1 Score:** 0.9333  

The model demonstrates strong performance, particularly in correctly identifying malignant cases.

---

## Model Saving
The trained model and scaler were saved for reuse and deployment:
- `svm_model.pkl`
- `scaler.pkl`

---

## Conclusion
The SVM-based approach provides reliable classification results for breast cancer diagnosis.  
This project highlights how machine learning can support **early detection** and **decision-making** in medical applications.

---

## Tools
Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook
