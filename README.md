# 🧠 Decision Tree Classifier: Bank Marketing Campaign

## 📌 Overview

This project builds a **Decision Tree Classifier** to predict whether a customer will **subscribe to a term deposit** based on demographic and behavioral data. The model is trained on the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

---

## 📂 Dataset

- **Source**: [Bank Marketing Dataset – UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **Format**: CSV (`bank.csv` with semicolon delimiter)
- **Description**: Contains 45,211 customer records with features like job, education, contact method, previous campaign outcome, and more.

---

## 🔍 Objective

- Encode categorical data
- Train a **Decision Tree Classifier**
- Evaluate with metrics: accuracy, confusion matrix, classification report
- Visualize the tree structure for interpretation

---

## 📊 Features Used

- **Demographics**: age, job, marital, education
- **Finance**: default status, housing/personal loan
- **Call Information**: contact method, last call duration, number of contacts
- **Marketing Outcome**: outcome of previous campaigns
- **Target Variable**: `y` (subscribed: yes/no)

---

## 🛠️ Tools & Libraries

- `pandas` – data manipulation  
- `numpy` – numerical operations  
- `seaborn`, `matplotlib` – visualizations  
- `scikit-learn` – model training, evaluation, encoding

---
## 🌳 Decision Tree Visualization

![Decision Tree](images/tree_plot.png)

## 📉 Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

  
