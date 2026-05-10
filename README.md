# Week 5 Day 1 — Supervised Learning Foundations

This project covers the mathematical foundations and practical implementation of supervised machine learning using Scikit-learn.

Topics implemented:
- Linear Regression
- Ridge Regression
- Lasso Regression
- Logistic Regression
- Model Evaluation
- Threshold Tuning
- Regularization
- Multicollinearity Analysis

---

# Project Structure

```text
week5_supervised_learning/
│
├── notebooks/
│   └── day1_regression.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Concepts Covered

## Linear Regression

Models relationships between features and continuous targets.


::contentReference[oaicite:0]{index=0}


Topics:
- Ordinary Least Squares
- Mean Squared Error
- Coefficient interpretation
- Baseline modeling

---

## Ridge & Lasso Regression

Regularization techniques used to reduce overfitting.

### Ridge (L2)

:contentReference[oaicite:1]{index=1}

### Lasso (L1)

:contentReference[oaicite:2]{index=2}

Topics:
- Bias-variance tradeoff
- Feature scaling
- Feature selection

---

## Logistic Regression

Binary classification using probability estimation.

:contentReference[oaicite:3]{index=3}

Topics:
- Sigmoid function
- Log-loss
- ROC-AUC
- Odds ratios
- Threshold tuning

---

# Evaluation Metrics

Regression:
- RMSE
- R² Score

Classification:
- Precision
- Recall
- F1 Score
- ROC-AUC
- Log Loss

---

# Libraries Used

- NumPy
- Pandas
- Scikit-learn

---

# Skills Practiced

- Supervised learning
- Regularization
- Feature scaling
- Model evaluation
- Classification threshold tuning
- Statistical interpretation

---

# Week 5 Day 2 — Decision Trees & Model Tuning

This project explores Decision Trees from both mathematical and practical machine learning perspectives using Scikit-learn.

Topics implemented:
- Gini Impurity
- Entropy & Information Gain
- Decision Tree Classification
- Overfitting Analysis
- Hyperparameter Tuning
- Feature Importance
- Learning Curves
- Bias-Variance Diagnosis

---

# Project Structure

```text
week5_supervised_learning/
│
├── notebooks/
│   ├── day1_regression.ipynb
│   └── day2_decision_trees.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Concepts Covered

## Gini Impurity

Measures node impurity in classification trees.

:contentReference[oaicite:0]{index=0}

Lower impurity means better class separation.

---

## Entropy

Measures uncertainty in a node.

:contentReference[oaicite:1]{index=1}

Used to calculate information gain during splitting.

---

## Information Gain

Decision trees select splits that maximize information gain.

:contentReference[oaicite:2]{index=2}

---

## Decision Trees

Tree-based models split data recursively to reduce impurity.

Topics:
- tree depth
- overfitting
- pruning
- decision boundaries

---

## Hyperparameter Tuning

GridSearchCV is used for:
- max_depth
- min_samples_leaf
- criterion
- pruning parameters

---

## Learning Curves

Learning curves help diagnose:
- high bias
- high variance
- overfitting
- underfitting

---

# Evaluation Metrics

Classification metrics used:
- Accuracy
- ROC-AUC
- Classification Report

---

# Libraries Used

- NumPy
- Pandas
- Scikit-learn

---

# Skills Practiced

- Tree-based modeling
- Hyperparameter tuning
- Cross-validation
- Bias-variance analysis
- Feature importance interpretation
- Overfitting diagnosis

---

# Week 5 Day 3 — Random Forest & Ensemble Learning

This project explores ensemble learning using Random Forests for both classification and regression tasks with Scikit-learn.

Topics implemented:
- Ensemble Learning
- Random Forest Classification
- Random Forest Regression
- Feature Importance
- OOB Scoring
- Hyperparameter Tuning
- Permutation Importance
- Prediction Intervals

---

# Project Structure

```text
week5_supervised_learning/
│
├── notebooks/
│   ├── day1_regression.ipynb
│   ├── day2_decision_trees.ipynb
│   └── day3_random_forest.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Concepts Covered

## Ensemble Learning

Random Forest combines multiple decision trees to reduce variance and improve generalization.

Ensemble variance:

:contentReference[oaicite:0]{index=0}

Topics:
- Bagging
- Variance reduction
- Feature bagging
- Tree decorrelation

---

## Random Forest Classification

Classification model trained for restaurant quality prediction.

Topics:
- OOB Score
- ROC-AUC
- Class balancing
- Feature importance

---

## Random Forest Regression

Regression model trained for apartment price prediction.

Topics:
- RMSE
- R² Score
- Prediction intervals
- Non-linear relationships

---

## Hyperparameter Tuning

RandomizedSearchCV used for tuning:
- n_estimators
- max_depth
- max_features
- min_samples_leaf
- min_samples_split

---

## Feature Importance

Two methods compared:
- Mean Decrease Impurity (MDI)
- Permutation Importance

---

# Evaluation Metrics

Classification:
- Accuracy
- ROC-AUC
- Classification Report

Regression:
- RMSE
- R² Score

---

# Libraries Used

- NumPy
- Pandas
- Scikit-learn

---

# Skills Practiced

- Ensemble learning
- Random Forest modeling
- Hyperparameter tuning
- Feature importance analysis
- OOB validation
- Regression and classification workflows

---

# Week 5 Day 4 — Model Evaluation & Validation

This project explores machine learning evaluation metrics and validation strategies for both classification and regression models using Scikit-learn.

Topics implemented:
- Confusion Matrix
- Precision & Recall
- F1 Score
- ROC-AUC vs PR-AUC
- Threshold Tuning
- Cross-Validation
- Stratified K-Fold
- Regression Metrics

---

# Project Structure

```text
week5_supervised_learning/
│
├── notebooks/
│   ├── day1_regression.ipynb
│   ├── day2_decision_trees.ipynb
│   ├── day3_random_forest.ipynb
│   └── day4_model_evaluation.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Concepts Covered

## Confusion Matrix

Used to evaluate classification predictions.

Topics:
- True Positives
- False Positives
- False Negatives
- True Negatives

---

## Precision & Recall

Precision:

:contentReference[oaicite:0]{index=0}

Recall:

:contentReference[oaicite:1]{index=1}

Topics:
- class imbalance
- business tradeoffs
- medical diagnosis intuition

---

## F1 Score

Balances precision and recall.

:contentReference[oaicite:2]{index=2}

---

## ROC-AUC vs PR-AUC

Evaluation of classification ranking performance.

Topics:
- imbalanced datasets
- fraud detection scenarios
- rare event classification

---

## Threshold Tuning

Classification probabilities converted into predictions using thresholds.

Topics:
- precision-recall tradeoff
- business cost optimization
- threshold sensitivity analysis

---

## Cross-Validation

Validation strategies implemented:
- K-Fold
- Stratified K-Fold
- TimeSeriesSplit

---

## Regression Metrics

Metrics implemented:
- MAE
- RMSE
- MAPE
- R² Score

---

# Libraries Used

- NumPy
- Pandas
- Scikit-learn

---

# Skills Practiced

- Model evaluation
- Validation strategies
- Classification analysis
- Imbalanced learning evaluation
- Regression metric comparison
- Threshold optimization

---

# How to Run

```bash
git clone https://github.com/MohammedMateen0/supervised_learning.git
pip install -r requirements.txt
jupyter notebook
```

Open:

```text
notebooks/day1_regression.ipynb
notebooks/day2_decision_trees.ipynb
notebooks/day3_random_forest.ipynb
notebooks/day4_model_evaluation.ipynb
```

---

# Author

Mohammed Mateen  
Machine Learning & Data Science May — 2026