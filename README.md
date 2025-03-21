Intrusion Detection System (IDS) Project
🚀 Overview
This project focuses on building a robust Intrusion Detection System (IDS) that detects and classifies network intrusions. Two machine learning models are developed:

Attack Classification Model: Multiclass classification for 12 types of network attacks.
Attack Detection Model: Binary classification (attack vs. no attack).
Both models employ advanced feature selection techniques, preprocessing pipelines, and ML/DL algorithms to achieve high accuracy and performance.

🎯 Objectives
Attack Classification Model:

Multiclass classification of 12 attack types.
Dataset: CIC-DS with 2.3 million records and 38 preprocessed features.
Attack Detection Model:

Binary classification for attack vs. no attack.
Dataset: UNSW-NB15 with 1.5 million records and 50 raw features (preprocessed).
🌟 Features
Ensemble Feature Selection: Combines multiple feature selection methods (Chi-square, RFE, etc.) via majority voting to identify the most relevant features.
Comprehensive Preprocessing:
Handling class imbalance (SMOTE/undersampling).
Scaling and normalization of features.
Dimensionality reduction (Ensemble_ feature_selection).
Model Implementation:
Algorithms: MLP, Random Forest, XGBoost, Decision Tree.
Comparative evaluation of models.
Performance Visualization:
ROC curves.
Confusion matrices.
Metrics comparison (accuracy, precision, recall, F1-score, ROC-AUC).
