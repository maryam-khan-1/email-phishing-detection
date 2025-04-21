# Email Phishing Detection

Personal ML project for classifying phishing emails using various classification algorithms.

## Overview

This project uses machine learning to detect phishing emails based on features from the [Email Phishing Dataset](https://www.kaggle.com/datasets/ethancratchley/email-phishing-dataset/data).

## Features

- Data exploration and feature correlation analysis
- Dimensionality reduction, sampling and transformation
- Models implemented: Decision Tree, Random Forest, Naive Bayes, Logistic Regression
- Performance evaluation with confusion matrices

## Requirements

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Results

Random Forest achieved the highest accuracy, followed by Decision Tree. Naive Bayes improved significantly after log transformation of skewed features.