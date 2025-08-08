# Logistic Regression on the Breast Cancer Dataset

This project focuses on binary classification using logistic regression on the Breast Cancer Wisconsin dataset, which includes steps for data pre-processing, model training and evaluation, and threshold tuning.

---

## 🔍 Problem

It is known that early detection of breast cancer is vital for successful treatment. Given a bunch of features extracted from digitized images of breast tissue, it is to be classified as **malignant (cancerous)** or **benign (non-cancerous)**.

---

## 🎯 Learning Objectives

- Learn how to fit and implement logistic regression for binary classification.
- Learn how to feature scale and train/test split.
- Learn how to evaluate a model using confusion matrix, precision, recall, and ROC-AUC.
- Learn about sigmoid function behavior and threshold tuning.

---

## 🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 📁 Dataset Overview

- **Source**: Breast Cancer Wisconsin Diagnostic Dataset
- **Target Column**: `diagnosis` (M = Malignant, B = Benign).
- **Features**: Mean, worst, and standard error values for 30 different cell nuclei measurements.

---

## 📊 Methodology

1. Load and pre-process the data.
2. Encode target column as `M = 1`, `B = 0`.
3. Train/test split the data.
4. Standardize features using `StandardScaler`.
5. Train a Logistic Regression model.
6. Evaluate using:
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC Curve and AUC score
7. Use the sigmoid outputs to tune the classification threshold.

---

## 📈 Evaluation Results

- **Accuracy**: ~97.3%
- **ROC-AUC Score**: ~0.997
- **Confusion Matrix**:
  ```
  [[70,  1],
   [ 2, 41]]
  ```

---

## 📌 Threshold Tuning

Currently, the model is using a sigmoid function.
