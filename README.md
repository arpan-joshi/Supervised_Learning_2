# Supervised Machine Learning: Part 2 (Tuning & Classification)

## 📌 Overview
This repository covers intermediate Supervised Machine Learning concepts. It focuses on preparing data for models, diagnosing and fixing model performance issues, applying regularization techniques, and introducing classification algorithms.

## 📚 Topics Covered

### 1. Feature Engineering (FE)
* **Encoding Data:** Transforming categorical/text data into numerical formats that machine learning algorithms can process.
* **The Dummy Variable Trap:** Understanding multicollinearity issues when creating dummy variables and how to avoid them.
* **Other FE Techniques:** Additional methods for shaping and scaling data for optimal model ingestion.

### 2. Model Performance: Overfitting vs. Underfitting
* **Diagnosis:** Learning how to identify whether a model is underfitting (high bias/too simple) or overfitting (high variance/memorizing noise).
* **Solutions:** Implementing strategies to correct poor model fit and improve generalization to unseen data.

### 3. Regularization Techniques
* **Lasso Regression (Algorithm 2):** Applying L1 Regularization to penalize absolute weights, useful for automatic feature selection.
* **Ridge Regression:** Applying L2 Regularization to penalize squared weights, preventing single features from dominating the model.
* **ElasticNet:** Using a hybrid approach that combines the penalties of both Lasso and Ridge regression.
* **LassoCV:** Utilizing cross-validation built into Lasso to automatically find the optimal alpha/penalty parameter.

### 4. Classification: Logistic Regression
* **Algorithm 3:** Moving from continuous predictions (Regression) to categorical predictions (Classification) using Logistic Regression.
* **Cost Function:** Understanding Log Loss (Cross-Entropy) and how it differs from Mean Squared Error.
* **Implementation:** Writing the Python code to train and deploy a Logistic Regression model.
