# Bio_Info_Final_Project
# Heart Disease Prediction Using Machine Learning

**Project Repository for BIOL Report**

Predict cardiovascular disease risk using demographic and clinical features from the UCI Heart Disease Dataset via supervised machine learning.

---

## Team Members
- **Rudra**: ML workflow development, model implementation, evaluation metrics, visualization generation, Methods/Results/Discussion writing
- **Utsav**: Exploratory data analysis, results interpretation, Introduction/Data sections, clinical relevance analysis
- **Trushit**: Documentation, project organization, reproducibility maintenance, README/ai_usage drafting, workflow structuring

---

## Repository Structure
├── artifacts/
│   └── heart_clean.csv              # Preprocessed dataset
├── results/
│   ├── cv_metrics.csv               # Cross-validation scores
│   └── test_metrics.csv             # Test set performance
├── figures/
│   ├── class_distribution.png       # Target variable balance
│   ├── correlation_heatmap.png      # Feature correlation matrix
│   ├── roc_curves.png               # ROC curves comparison
│   ├── confusion_matrices.png       # Confusion matrices
│   └── feature_importance.png       # Random Forest feature importance
├── notebooks/
│   └── heart_disease_analysis.ipynb # Main analysis notebook
├── scripts/
│   ├── preprocess.py                # Data cleaning pipeline
│   ├── train_models.py              # Model training script
│   └── evaluate.py                  # Evaluation and visualization
├── README.md
├── ai_usage.md
└── requirements.txt


---

## Installation & Setup

### Requirements
- Python 3.12
- NumPy, pandas, matplotlib
- scikit-learn (≥1.4)

### Quick Start
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd heart-disease-prediction

2.Install dependencies:
  pip install -r requirements.txt

3.open and run the Jupyter notebook:
  jupyter notebook notebooks/heart_disease_analysis.ipynb

