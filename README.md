# Fetal Health Classifier

A predictive classification model to analyze fetal health using cardiotocography (CTG) data.

## Problem Statement
Early detection of fetal distress can save lives. This model classifies fetal health 
into Normal, Suspect, or Pathological categories using CTG features.

## Tech Stack
- Python, Scikit-learn, Pandas, NumPy
- Gradient Boosting, Random Forest
- Seaborn, Matplotlib

## Results
- Achieved high classification accuracy using Gradient Boosting
- Evaluated with multi-class ROC/AUC analysis, confusion matrices, and feature importance mapping
- Dataset: UCI Fetal Health Dataset (2126 samples, 21 features)

## Key Features
- Data scaling and preprocessing pipeline
- Feature importance visualization
- Multi-class ROC/AUC evaluation

## How to Run
pip install -r requirements.txt
python fetal_health.py
