 Task4
# Logistic Regression - Breast Cancer Classification

This project is part of an AI & ML internship task. The goal is to build a binary classifier using **Logistic Regression** to predict whether a tumor is malignant or benign using the Breast Cancer Wisconsin dataset.

---

##  Objective

To build a binary classification model using logistic regression and evaluate its performance using common classification metrics and visualizations.

---

##  Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

##  Dataset

**Breast Cancer Wisconsin (Diagnostic) Data Set**

- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Features**: 30 real-valued features computed from a digitized image of a breast mass
- **Target**: 
  - Malignant (`M`) → 1
  - Benign (`B`) → 0

---

##  Project Workflow

1. **Data Preprocessing**:
   - Load dataset
   - Drop irrelevant columns (`id`, `Unnamed: 32`)
   - Convert categorical labels to numeric

2. **Data Splitting**:
   - Train-test split (80/20)
   - Feature standardization using `StandardScaler`

3. **Model Building**:
   - Logistic Regression using `sklearn.linear_model.LogisticRegression`

4. **Evaluation**:
   - Confusion Matrix
   - Precision, Recall, F1-score
   - ROC-AUC Score and Curve
   - Sigmoid function visualization

---

##  Results

- **Precision**: ~ (e.g., 0.97)
- **Recall**: ~ (e.g., 0.95)
- **ROC-AUC**: ~ (e.g., 0.99)

*(Values may vary depending on random state and dataset version)*

---

##  Visualizations

- ROC Curve
- Sigmoid Function Plot

---


