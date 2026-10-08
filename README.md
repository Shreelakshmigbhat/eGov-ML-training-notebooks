# eGov ML — Complaint Intelligence & Severity Analysis

Machine Learning pipelines for intelligent analysis of citizen complaints in the eGov platform.

The repository contains model training workflows for complaint classification and severity prediction using NLP, classical machine learning, and transformer-based representations.

---

## Overview

The eGov ML system focuses on extracting actionable intelligence from citizen complaints.

The current repository contains two major ML pipelines:

1. **Complaint Service-Code Classification**
   - TF-IDF feature extraction
   - Linear Support Vector Machine (LinearSVC)
   - Stratified 5-Fold Cross-Validation
   - Accuracy, Macro F1, and Weighted F1 evaluation

2. **Complaint Severity Analysis**
   - Sentence Transformer embeddings
   - CatBoost classification/regression pipeline
   - Severity-oriented feature engineering
   - Model evaluation and prediction

These models are intended to support downstream eGov workflows such as complaint routing, prioritization, escalation, and administrative decision-making.

---

## Repository Structure

```text
eGov-ML/
│
├── LSVM+TFIDF.ipynb
│   └── Complaint Service-Code Classification
│
├── severity_training_latest.ipynb
│   └── Complaint Severity Analysis
│
├── README.md
│
└── ...