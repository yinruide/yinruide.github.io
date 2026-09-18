---
layout: page
title: Click-Through Rate Prediction
description: End-to-end CTR pipeline on the 4M-row Avazu dataset
img: assets/img/ctr.jpg
importance: 3
category: earlier
github: https://github.com/yinruide/Click-Through-Rate-Prediction
---

*Mar 2025* · [GitHub](https://github.com/yinruide/Click-Through-Rate-Prediction)

An end-to-end CTR prediction pipeline on a 4M-row, 11-day Avazu ad click dataset, covering EDA, feature engineering, modeling, and interpretability.

- Trained and compared **Logistic Regression** (baseline), **Random Forest**, **LightGBM**, **XGBoost**, **DeepFM** (PyTorch), and an optimized **weighted ensemble** with RandomizedSearchCV tuning, reducing LogLoss by 8.7%.
- Conducted **SHAP** feature importance, calibration analysis (ECE = 0.003), error analysis, and segment-level evaluation — confirming no post-hoc calibration was needed and that target-encoded features dominated.
- Implemented VRAM-aware GPU training for DeepFM on an 8GB consumer GPU with batched inference, pinned memory, and per-epoch cache management.

**Stack:** LightGBM · XGBoost · PyTorch · DeepFM · SHAP
