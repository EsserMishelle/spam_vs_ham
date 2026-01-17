# spam_vs_ham
End-to-end spam email classification using supervised machine learning with a focus on precision, recall, and real-world decision tradeoffs

# Spam vs Ham Email Classification

## Overview
This project implements an end-to-end machine learning workflow to classify emails as spam or non-spam (ham). The analysis emphasizes precision, recall, and F1-score due to class imbalance and real-world decision tradeoffs.

## Data
The dataset consists of labeled email messages categorized as spam or ham. Text data was cleaned and transformed into numerical features suitable for supervised learning.

## Methods
- Text preprocessing and feature extraction using TF-IDF
- Supervised classification models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Model evaluation focused on class imbalance considerations

## Evaluation
Models were evaluated using:
- Confusion matrices
- Precision, recall, and F1-score
- ROC curves

Performance comparisons highlight the tradeoffs between model interpretability, recall of spam messages, and false positive rates.

## Key Findings
- Logistic regression provided a balanced performance across precision and recall.
- Tree-based models achieved high precision but suffered from recall degradation under depth constraints, demonstrating underfitting behavior.
- Model selection depends on tolerance for false positives versus missed spam.

## Tools
Python, pandas, scikit-learn, matplotlib, Jupyter Notebook
