# ICS Intrusion Detection with SWaT

A machine learning pipeline for detecting attacks on Industrial Control Systems, evaluated on the SWaT dataset. Compares two supervised models (Random Forest, XGBoost) against an unsupervised baseline (Isolation Forest).

Project for CIS 5370 Principles of Cybersecurity.

## Dataset

SWaT dataset from Kaggle:
https://www.kaggle.com/datasets/vishala28/swat-dataset-secure-water-treatment-system

## Requirements

- Python 3
- pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn
- Kaggle API token for dataset download

## Usage

Open the notebook in Google Colab or Jupyter and run all cells. The pipeline handles preprocessing, feature engineering, training, and evaluation end to end.

## Results

| Model | Precision | Recall | F1 |
|-------|-----------|--------|------|
| Random Forest    | 0.9993 | 0.9989 | 0.9991 |
| XGBoost          | 0.9979 | 0.9849 | 0.9913 |
| Isolation Forest | 0.7868 | 0.6462 | 0.7096 |
