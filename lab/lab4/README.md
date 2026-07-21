# Lab 4: Regression and Classification Evaluation Metrics

This folder contains the implementation of the **K-Nearest Neighbours (KNN)** classification algorithm on the **Breast Cancer Wisconsin Diagnostic Dataset**, an analysis of its performance using different validation techniques, and an evaluation using classification metrics.

---

## Aim
To implement the **K-Nearest Neighbours (KNN)** classification algorithm on the **Breast Cancer Wisconsin Diagnostic Dataset**, analyze its performance using different validation techniques, and evaluate the model using classification metrics. The lab also compares these metrics with the regression evaluation metrics studied in **Linear Regression (Lab 3).**

---

## Objectives
After completing this lab, you should be able to:
- Understand how the KNN classification algorithm works.
- Prepare datasets for machine learning.
- Apply feature scaling using `StandardScaler`.
- Perform different train-test splits (80:20, 70:30, 90:10).
- Select an appropriate value of **K** using heuristic methods ($K = \sqrt{n}$).
- Evaluate model performance using Cross Validation (5-Fold and 10-Fold).
- Interpret classification evaluation metrics (Accuracy, Precision, Recall, F1 Score).
- Understand ROC Curve and ROC-AUC.
- Compare regression evaluation metrics with classification metrics.
- Analyze the advantages and limitations of KNN.

---

## Folder Structure
```
Lab4_KNN/
│
├── data/
│   └── breast_cancer.csv
│
├── notebooks/
│   └── Lab4_KNN.ipynb
│
├── images/
│   ├── accuracy_vs_k.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── decision_boundary_k1.png
│   ├── decision_boundary_k5.png
│   ├── decision_boundary_k10.png
│   └── decision_boundary_k20.png
│
├── README.md
└── requirements.txt
```

---

## Setup Instructions

1. **Activate Python Virtual Environment:**
   If you are running locally:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook notebooks/Lab4_KNN.ipynb
   ```
