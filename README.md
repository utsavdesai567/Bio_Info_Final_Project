# Bio_Info_Final_Project  
# Heart Disease Prediction Using Machine Learning  

This repository contains our final project for the BIOL course, focused on predicting heart disease using machine learning techniques and clinical features from the UCI Heart Disease dataset. The project implements a complete, reproducible workflow with preprocessing, model training, evaluation, and visualization.

---

## 📌 Project Summary

We evaluate how well machine learning models can predict heart disease using routinely collected clinical variables.  
The project includes:

- **Preprocessing:** StandardScaler + OneHotEncoder (ColumnTransformer)  
- **Models:** Logistic Regression, Random Forest  
- **Validation:** 5-fold stratified cross-validation  
- **Metrics:** Accuracy, F1-Score, ROC-AUC  
- **Visualizations:**  
  - Correlation heatmap  
  - ROC curves  
  - Feature importances  

---

## 📂 Dataset

We use the **UCI Heart Disease Dataset**, which must be placed manually in the project folder as:


---

## 📊 Obtained Results

| Model               | Accuracy | F1 Score | ROC-AUC |
|--------------------|----------|----------|---------|
| Logistic Regression | 0.787    | 0.817    | 0.871   |
| Random Forest       | **0.803** | **0.838** | **0.903** |

Random Forest outperforms Logistic Regression across all evaluation metrics.

---

## 👥 Team Members

- **Rudra** – ML workflow development, model implementation, evaluation, results/figures  
- **Utsav** – Exploratory data analysis, interpretation, introduction/data writing, clinical relevance  
- **Trushit** – Documentation, repo organization, reproducibility, README + AI usage drafting  

---

## ⚙️ Installation & Setup

### Requirements
- Python **3.12**
- `numpy`, `pandas`, `matplotlib`
- `scikit-learn >= 1.4`

---

## 🚀 Quick Start

### 1. Clone the repository

`git clone <repository-url>
cd heart-disease-prediction`

---

### 2. Install dependencies

`pip install -r requirements.txt`

### 3. Open and run the notebook
`jupyter notebook notebooks/heart_disease_analysis.ipynb`


