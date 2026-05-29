# Basics of AI/ML: A Hands-on Workshop

This repository contains materials and notes from the "Basics of AI/ML: A Hands-on Workshop".

## 🎯 Workshop Goals
* Demystify AI and ML concepts in a beginner-friendly manner [1].
* Understand **what** AI/ML is, **why** and **when** to use it, and its **impacts** [1].
* Provide hands-on learning experiences [1].

## 🧠 Core Concepts
* **Artificial Intelligence (AI):** A set of technologies empowering computers to learn, reason, and perform advanced tasks that traditionally required human intelligence [3].
* **Machine Learning (ML):** A subset of AI allowing machines to learn from data without explicit programming [4].
* **Types of ML:** Supervised, Unsupervised, Semi-supervised, and Reinforcement Learning [4].
* **Common ML Tasks:** Regression, Classification, Dimensionality Reduction, and Association Rule Learning [4].

## 📊 Data Exploration and Preprocessing
* **Know Your Data:** Inspect dataset structure and quality using tools like `df.shape`, `df.info()`, `df.describe()`, and visualize to reflect correlations [4, 5].
* **Handling Unbalanced Datasets:** Techniques include Random Undersampling, Random Oversampling, and SMOTE (Synthetic Minority Over-sampling Technique) [5, 6].
* **Data Preprocessing Techniques:**
  * **Missing Values:** Handling missing data via deletion or imputation [6].
  * **Outliers:** Detection and mitigation using IQR or Z-Score methods [6].
  * **Categorical Values:** Encoding methods like Label, One-Hot, Ordinal, and Binary Encoding [6].
  * **Feature Scaling:** Min-Max Scaler and Standard Scaler (Z-score normalization) [7].
* **Feature Selection:** Mitigates the "Curse of Dimensionality" and prevents overfitting using methods like Linear or Kernel PCA [7].

## 📈 Supervised Learning
### Regression (Predicting Continuous Values)
* **Types:** Linear, Multiple, and Polynomial Regression [7, 8].
* **Regularization:** ElasticNet, Lasso (L1), Ridge (L2) to prevent overfitting [8].
* **Evaluation Metrics:** MSE, MAE, RMSE (penalizes large errors), SMAPE, MAPE, and R² [8, 9].

### Classification (Predicting Categories)
* **Types:** Binary, Multiclass, and Multilabel [10].
* **Key Algorithms:** 
  * Logistic Regression (discrete outcomes) [10].
  * Naive Bayes (Gaussian, Multinomial, Bernoulli) [10, 11].
  * Support Vector Machine (SVM) utilizing Kernel Tricks (RBF, Polynomial, Sigmoid) [12].
  * K-Nearest Neighbors (KNN) utilizing proximity and majority voting [13, 14].
  * Decision Trees [14].
* **Evaluation Metrics:** Accuracy, Recall, Precision, F1 score, log-loss, Confusion Matrix, and AUC (Area Under the Curve) [11, 15].

## 🌳 Ensemble Methods
* Machine learning techniques that aggregate multiple models to produce better predictions, lower variance, and reduce noise [16].
* **Random Forest:** Combines multiple decision trees, using majority voting for classification and averaging for regression [16, 17].


## ⚖️ The Bias-Variance Tradeoff
* The optimization process aims to balance model simplicity and complexity: *Total Error = Bias² + Variance + Irreducible Error* [21].
* **Underfitting (High Bias, Low Variance):** Errors are consistently high due to overly simplistic models or insufficient training [22]. Overcome with more complex models or better feature engineering [22].
* **Overfitting (Low Bias, High Variance):** Memorizes training data 
