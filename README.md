# Spam vs Ham Email Classification
## Overview
This project implements an end-to-end supervised machine learning workflow, from text preprocessing through model evaluation, to classify emails as spam or non-spam (ham). The analysis emphasizes precision, recall, and F1-score due to class imbalance and real-world decision tradeoffs.

## Data
The dataset consists of labeled email messages categorized as spam or ham. Text data was cleaned and transformed into numerical features suitable for supervised learning.

## Methods
- Text preprocessing and feature extraction using TF-IDF
- Supervised classification models:
  - Logistic Regression
  - Random Forest
- Model evaluation focused on class imbalance considerations

## Evaluation
Models were evaluated using:
- Confusion matrices
- Precision, recall, and F1-score
- ROC curves
Performance comparisons highlight the tradeoffs between model interpretability, recall of spam messages, and false positive rates.

## Key Findings
- Logistic Regression provides a strong, interpretable baseline with balanced precision and recall.
- Random Forest achieves higher precision and robust performance, making it preferable when false positives are more costly than missed spam.
- Model selection depends on the relative cost of false positives versus false negatives.

## Tools
Python, pandas, scikit-learn, matplotlib, Jupyter Notebook
