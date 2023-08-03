---
title: "Machine Learning - Supervised Learning on Heart Disease and Cancer Datasets"
excerpt: "This project reviews five machine learning algorithms across two medical datasets, Breast Cancer (BC) and Heart Disease (HD), obtained from UCI’s Machine Learning Repository. The goal is to predict Breast Cancer presence and detect Heart Disease. The analysis includes dataset overviews, algorithm discussions, performance comparisons, and conclusions."
collection: portfolio
---

## Summary: Machine Learning Algorithm Analysis on Medical Datasets

**Introduction:**
This paper reviews five machine learning algorithms across two medical datasets, Breast Cancer (BC) and Heart Disease (HD), obtained from UCI’s Machine Learning Repository. The goal is to predict Breast Cancer presence and detect Heart Disease. The analysis includes dataset overviews, algorithm discussions, performance comparisons, and conclusions.

**Datasets Overview:**

A. **Breast Cancer:** 569 samples, 30 prediction features, imbalanced class, computed from digitized breast mass images.

B. **Heart Disease:** 827 samples, 75 prediction features, binary target, 13 commonly used features.

**Interesting Aspects:**
These datasets are significant for early medical condition detection, offering potential for better treatment. BC focuses on breast lump attributes, while HD mixes symptoms and individual characteristics.

**Algorithm Analysis (Recall, ROC AUC, F1):**

A. **Decision Tree:** Explores maximum depth and leaf nodes impact.

B. **AdaBoost:** Investigates base estimator depth and weak learners influence.

C. **k-Nearest Neighbors:** Analyzes k-neighbors and distance formula.

D. **Multilayer Perceptron:** Examines hidden layers, alpha, and activation functions.

E. **Support Vector Classifier:** Explores kernels and regularization parameter.

**Conclusion and Improvements:**
1. Datasets: Consider refreshing datasets with modern healthcare data collection devices to improve accuracy.
2. Feature Expansion: Include family history features and background data to enhance models' predictive power.
3. Dataset Representation: Ensure datasets are diverse to account for population variations.
4. Feature Engineering: Experiment with various feature engineering methods to optimize model performance.
5. Algorithm Enhancements: Explore Random Forests for Decision Trees, larger AdaBoost ensembles, and scaling for KNNs.
6. Validation: Implement Stratified K-Fold Validation for better handling of imbalanced classes.
7. Runtime Optimization: Consider algorithm runtime for practical implementation.

By systematically analyzing these algorithms on medical datasets, this paper offers insights into their performance and potential enhancements for more accurate predictions and improved patient outcomes.
