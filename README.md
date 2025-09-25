# 🚀 Startup Success Prediction

This repository contains a **data mining project** developed as part of the IN015 - Data Mining course.  
The goal is to **predict startup success** using real-world data and machine learning techniques.

---

## 📂 Project Overview

Startups are inherently risky, but certain indicators—such as **social media activity, engagement ratios, and web presence**—may help assess their probability of success.  
In this project, we:

- Performed **data cleaning and preprocessing** on a dataset of 700 startups.
- Handled missing values with domain-based imputations.
- Applied **exploratory data analysis (EDA)**, correlation heatmaps, and visualizations.
- Built and compared multiple machine learning models:
  - Dummy Classifier (baseline)
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost

Our best-performing model was **Random Forest**, achieving ~88.9% precision in predicting successful startups.

---

## 🛠️ Tech Stack

- **Languages**: Python 3  
- **Libraries**:
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `xgboost`
  - Evaluation: `metrics`, `cross-validation`

---

## 📊 Results

- **Dummy Classifier**: Very poor (predicts all startups fail).
- **Logistic Regression**: ~75% precision.
- **Decision Tree**: Weak performance (overfits easily).
- **Random Forest**: **Best model** with 88.9% precision.
- **XGBoost**: Promising results, comparable to Random Forest.
