# Module 2: Advanced Machine Learning

Building on the fundamentals from Module 1, this module dives deep into ensemble methods, feature engineering, and model optimization with a focus on geospatial applications.

## Learning Objectives

- Understand ensemble learning approaches (Bagging vs Boosting).
- Implement Random Forest and Gradient Boosted Trees (XGBoost).
- Engineer meaningful features from spectral imagery (Spectral Indices).
- Apply hyperparameter tuning techniques (Randomized Search, Grid Search).
- Handle imbalanced datasets using SMOTE and other resampling techniques.

## Prerequisites

- Completed Module 1: Basic Machine Learning.
- Familiarity with `pandas`, `numpy`, and `scikit-learn`.
- Basic understanding of remote sensing concepts (optional but helpful).

## Topics Covered

| Topic                     | Description                                             |
| :------------------------ | :------------------------------------------------------ |
| **Random Forests**        | Ensemble of decision trees, bagging, feature importance |
| **XGBoost**               | Gradient boosting, regularization, early stopping       |
| **Spectral Indices**      | NDVI (vegetation), NDWI (water), NDBI (buildings)       |
| **Hyperparameter Tuning** | RandomizedSearchCV, GridSearchCV, cross-validation      |
| **Class Imbalance**       | SMOTE, class weights, evaluation with macro F1          |

## Hands-on Exercises

### 1. [Land Cover Classification](./land_cover_classification.ipynb)

Multi-spectral satellite imagery classification using Random Forest and XGBoost.

**What you'll learn:**

- Load and preprocess multi-band satellite imagery
- Calculate spectral indices (NDVI, NDWI, NDBI)
- Train ensemble classifiers for land cover mapping
- Evaluate with confusion matrices and classification reports

**Dataset:** EuroSAT Sentinel-2 satellite imagery (10 land cover classes)

**Estimated time:** 45-60 minutes

## Resources

- [Scikit-learn Ensemble Methods](https://scikit-learn.org/stable/ensemble.html)
- [XGBoost Documentation](https://xgboost.readthedocs.io/)
- [Spectral Indices Overview](https://www.indexdatabase.de/)
- [Handling Imbalanced Data](https://imbalanced-learn.org/stable/)

## Next Steps

After completing this module, proceed to [Module 3: Deep Learning Foundations](../3_deep_learning/) to learn about neural networks and CNNs for image classification.
