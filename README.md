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

# How to Run

```bash
git clone  https://github.com/MohammedMateen0/supervised_learning.git
pip install -r requirements.txt
jupyter notebook
```

Open:

```text
notebooks/day1_regression.ipynb
notebooks/day2_decision_trees.ipynb
```

---

# Author

Mohammed Mateen  
Machine Learning & Data Science May — 2026
