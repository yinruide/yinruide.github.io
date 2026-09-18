---
layout: page
title: Credit Card Fraud Detection
description: Classification on a highly imbalanced transaction dataset
img: assets/img/fraud.jpg
importance: 4
category: earlier
github: https://github.com/yinruide/Credit-Card-Fraud-Detection
---

*Jan 2025* · [GitHub](https://github.com/yinruide/Credit-Card-Fraud-Detection)

An end-to-end classification pipeline predicting card transaction fraud on a highly imbalanced dataset (284K transactions, 0.17% fraud), with ~10% AUPRC improvement over baseline.

- Systematically compared **Logistic Regression**, **Random Forest**, **XGBoost**, and **LightGBM** across resampling strategies (Random Oversampling, **SMOTE**, **ADASYN**, SMOTE+Tomek) using RandomizedSearchCV.
- Benchmarked unsupervised anomaly detection with **Isolation Forest** and an **Autoencoder** (PyTorch).
- Applied **SHAP** for global and local interpretability — summary plots, dependence plots, and per-transaction waterfall explanations.
- Conducted threshold optimization with **F2** scoring to demonstrate precision-recall trade-offs for production deployment.

**Stack:** scikit-learn · XGBoost · LightGBM · PyTorch · SHAP · imbalanced-learn
