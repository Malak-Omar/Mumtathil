# Mumtathil
# Mumtathil (مُمتثِل): Automatic PDPL Compliance Identification System of Arabic Privacy Policies Documents

## Overview

Mumtathil is an automated system that evaluates the compliance of Arabic privacy policy documents with the Saudi Personal Data Protection Law (PDPL) using multi-label classification (MLC) techniques. The system achieved an F-score of 92% using Support Vector Machine (SVM) with TF-IDF representation.

## Authors

- Malak Mashaabi — King Saud University
- Hend Al-Khalifa — King Saud University

## Repository Contents

| File | Description |
|------|-------------|
| `Dataset.csv` | Saudi Privacy Policy Dataset (1,888 privacy policies labeled with PDPL categories) |
| `MachineLearning Code.ipynb` | SVM, Random Forest, and Logistic Regression experiments with TF-IDF and Word2Vec |
| `TransformersCode.ipynb` | AraBERT and CamelBERT experiments with overlap technique for long documents |

## Requirements

```bash
pip install -r requirements.txt
```

## Models

- **Machine Learning:** SVM, Logistic Regression, Random Forest (with TF-IDF and Word2Vec)
- **Transformers:** AraBERT, CamelBERT (with overlapping chunks for long documents)

## Dataset

- 1,888 Arabic privacy policies
- 9 PDPL compliance categories
- Augmented with synthetic data generated using ChatGPT
- 7-fold cross-validation
