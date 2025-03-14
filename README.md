# Polaris-potency-report
This repository contains a machine learning workflow for predicting protein-related properties (SARS and MERS datasets). The pipeline preprocesses data using tools like DataWarrior and OCHEM, computes descriptors (e.g., PubChem, ECFP, Chemprop), and applies feature selection with SHAP and genetic algorithms. Models such as XGBoost, LightBoost, CatBoost, and SVR are trained and evaluated using 5-fold cross-validation, achieving competitive performance.

## Key Features
- Data preprocessing: NaN removal, duplicate handling, and feature filtering.
- Descriptor calculation: OCHEM, scikit-fingerprints, Chemprop embeddings.
- Feature selection: SHAP values, genetic algorithms, PCA.
- Consensus modeling: Averaged predictions from multiple models.
