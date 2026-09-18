---
layout: page
title: Medical Insurance Cost Predictor
description: Two-stage routing pipeline with a Streamlit interface
img: assets/img/insurance.jpg
importance: 2
category: featured
github: https://github.com/yinruide/Insurance-Cost-Predictor
---

*Apr 2026 – May 2026* · [GitHub](https://github.com/yinruide/Insurance-Cost-Predictor)

A **Streamlit** web app predicting annual medical insurance costs, with interactive data exploration, live prediction, and side-by-side model comparison.

- Designed a two-stage pipeline using a binary classifier to route inputs to subgroup-specific regressors, improving prediction on heterogeneous populations.
- Trained and evaluated **Linear Regression**, **Random Forest**, **XGBoost**, **MLP**, **Mixture Density Network**, and **Quantile Regression** with hyperparameter tuning via **GridSearchCV**.
- Leveraged **SHAP** for feature importance visualization and **K-means** clustering for exploratory data validation.

**Stack:** Streamlit · scikit-learn · XGBoost · PyTorch · SHAP
