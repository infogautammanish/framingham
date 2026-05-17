# framingham
AI-powered cardiovascular disease prediction project using the Framingham Heart Study dataset. Includes machine learning, deep learning, explainable AI, Bayesian modeling, federated learning, graph neural networks, and advanced healthcare analytics techniques.

# ❤️ Framingham Heart Disease Prediction

A machine learning and AI driven cardiovascular risk prediction project built using the **Framingham Heart Study dataset**. This notebook explores end to end data preprocessing, feature engineering, predictive modeling, model evaluation, explainability, uncertainty estimation, and advanced AI concepts for healthcare analytics.

The project blends classic machine learning with experimental deep learning, Bayesian modeling, federated learning, graph neural networks, reinforcement learning, and explainable AI.

---

# 📌 Project Objectives

* Predict the likelihood of **10-year Coronary Heart Disease (CHD)** risk.
* Compare multiple machine learning algorithms.
* Handle imbalanced medical datasets.
* Improve prediction quality using feature engineering.
* Interpret predictions using explainable AI.
* Explore advanced healthcare AI techniques.

---

# 🧠 Technologies & Libraries Used

## Core Libraries

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn

## Machine Learning

* Scikit-learn
* XGBoost
* LightGBM
* Imbalanced-learn

## Deep Learning

* TensorFlow / Keras
* PyTorch
* Torch Geometric

## Explainability & AI Research

* SHAP
* DiCE-ML
* DoWhy
* PyMC
* ArviZ

---

# 📂 Dataset

The project uses the **Framingham Heart Study dataset**, which contains patient health records and cardiovascular risk indicators.

## Example Features

* Age
* Gender
* Smoking status
* Blood pressure
* Cholesterol
* Diabetes
* BMI
* Heart rate
* Glucose levels

## Target Variable

* `TenYearCHD`

  * `0` → No CHD risk
  * `1` → CHD risk within 10 years

---

# ⚙️ Project Workflow

## 1. Data Loading & Exploration

* Dataset inspection
* Shape analysis
* Missing value handling
* Statistical summaries

## 2. Data Preprocessing

* Missing value treatment
* Feature scaling
* Data cleaning
* Train-test split

## 3. Feature Engineering

Advanced engineered features include:

* Interaction features
* Risk ratios
* Combined clinical indicators
* Derived cardiovascular metrics

---

# 🤖 Machine Learning Models

The notebook experiments with multiple predictive models:

## Traditional Models

* Logistic Regression
* Random Forest
* Gradient Boosting
* Support Vector Machine
* Bayesian Ridge

## Advanced Models

* XGBoost
* LightGBM
* Ensemble Voting Classifier
* Stacking Classifier

---

# ⚖️ Imbalanced Data Handling

Medical datasets often suffer from class imbalance. The project explores:

* SMOTE
* ADASYN
* Random Under Sampling
* SMOTEENN

---

# 📊 Model Evaluation

Evaluation techniques used:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Precision-Recall Curve
* Cross Validation
* Calibration Analysis

---

# 🔍 Explainable AI (XAI)

The notebook includes explainability techniques for medical decision support:

## SHAP Analysis

* Feature importance
* Local prediction explanations

## Counterfactual Explanations

Using DiCE-ML to answer:

> “What changes would reduce a patient’s CHD risk?”

---

# 🧪 Advanced Research Concepts Included

This project also explores several experimental healthcare AI ideas:

## Bayesian Modeling

* Probabilistic risk estimation
* Uncertainty-aware predictions

## Federated Learning Simulation

* Multi-center healthcare training simulation
* Privacy-preserving learning concepts

## Graph Neural Networks (GNNs)

* Patient relationship modeling
* Graph-based healthcare representation

## Reinforcement Learning

* Experimental treatment strategy environments

## Meta Learning

* Few-shot cardiovascular prediction experiments

## Uncertainty Quantification

* Bootstrap-based uncertainty estimation
* Confidence interval analysis

---

# 🏥 Clinical Decision Support System

The notebook implements a basic clinical decision support framework that:

* Predicts patient risk
* Stratifies patients into risk categories
* Assists in healthcare interpretation

---

# 💾 Model Saving & Deployment Utilities

The project contains utilities for:

* Saving trained models
* Exporting metadata
* Creating reusable prediction pipelines

---

# 🚀 How to Run

## 1. Clone Repository

```bash
git clone <repository-url>
cd framingham-heart-disease-prediction
```

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

## 3. Run Notebook

```bash
jupyter notebook framingham.ipynb
```

---

# 📦 Suggested Requirements

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
xgboost
lightgbm
tensorflow
torch
torch-geometric
shap
dice-ml
dowhy
pymc
arviz
joblib
networkx
```

---

# 📈 Potential Improvements

* Build a Streamlit or Flask web app
* Deploy model using FastAPI
* Add real-world hospital datasets
* Perform hyperparameter optimization
* Add survival analysis
* Integrate electronic health records (EHR)

---

# 🎯 Future Scope

This project can evolve into:

* AI-powered preventive healthcare systems
* Smart hospital analytics platforms
* Personalized cardiovascular risk assistants
* Clinical research support tools

---

# 👨‍💻 Author

**Manish Kumar**

Domain Interests:

* Data Science
* Machine Learning
* Healthcare AI
* Deep Learning
* Explainable AI

---
