# Diabetes ML Comparative Analysis

A comparative machine learning study for diabetes prediction using multiple classification algorithms, hyperparameter optimization, class balancing, and ensemble learning.

## Overview
This project evaluates and compares multiple machine learning models on a diabetes prediction dataset through a complete ML pipeline including:

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature scaling
- Class imbalance handling using SMOTE
- Feature importance analysis
- Hyperparameter optimization
- Cross-validation
- Voting ensemble model

## Algorithms Evaluated
The following classifiers are compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- XGBoost
- Proposed Voting Ensemble Classifier

## Optimization Techniques Used
Three model optimization strategies are compared:

1. Default Hyperparameters (DHP)
2. Grid Search Cross Validation (GSCV)
3. Randomized Search Cross Validation (RSCV)

## Features of This Project
- Comparative performance benchmarking
- 5-fold stratified cross-validation
- SMOTE for class balancing
- SelectKBest and Random Forest feature importance
- ROC-AUC analysis
- Confusion matrices
- Performance heatmaps
- Radar charts
- Ensemble voting classifier

## Evaluation Metrics
Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

## Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- XGBoost

## Project Structure

```bash
.
├── comparative_analysis.py
├── dataset/
├── results/
│   ├── figures/
│   └── csv_tables/
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/diabetes-ml-comparative-analysis.git
cd diabetes-ml-comparative-analysis
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost
```

## Run the Project

```bash
python comparative_analysis.py
```

## Output
The project generates:

### Figures
- Feature distributions
- Correlation heatmaps
- ROC curves
- Confusion matrices
- Accuracy/F1 comparisons
- Radar charts

### Tables
- Model comparison results
- Cross-validation results
- Best hyperparameters
- Feature importance rankings

## Proposed Ensemble Model
A soft voting ensemble is implemented combining:

- Logistic Regression
- Random Forest
- SVM
- XGBoost
- KNN

Designed to improve diabetes prediction performance over individual models.

## Dataset
Dataset used:
Diabetes Prediction Dataset (Kaggle)

You can replace with your dataset source link here.

## Future Improvements
- Deep learning models
- Explainable AI (SHAP/LIME)
- Feature engineering
- Deployment with Streamlit/Flask
- Clinical decision support integration

## Author
Your Name

## License
MIT License
