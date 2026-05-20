
# Credit Risk Analysis and Scoring Model

## Project Overview

This project focuses on the development of a credit risk classification model using the German Credit Dataset from the UCI Machine Learning Repository.

The objective of the analysis is to identify high-risk customers using demographic and financial information through statistical modeling and machine learning techniques.

A Logistic Regression model was implemented in Python due to its balance between predictive performance and interpretability. The project also includes a Power BI dashboard for business-oriented visualization and risk monitoring.

The final model achieved a ROC-AUC of approximately 0.80 and was used to create a credit scoring system capable of segmenting customers into different risk categories.

---

## Dataset

- Source: UCI Machine Learning Repository
- Dataset: German Credit Dataset
- Observations: 1000
- Target Variable:
  - `1 = Good Credit`
  - `0 = Bad Credit`

The dataset contains both numerical and categorical variables related to:
- loan characteristics
- savings and checking account status
- employment duration
- demographic information
- financial reliability

---

## Methodology

The project workflow included:

- Exploratory Data Analysis (EDA)
- Missing values check
- One-Hot Encoding for categorical variables
- Train/Test Split using stratified sampling
- Logistic Regression modeling
- Multicollinearity analysis using VIF
- Outlier detection and removal using IQR
- Threshold tuning
- Model evaluation through classification metrics

---

## Model Performance

| Metric | Value |
|---|---|
| ROC-AUC | ~0.80 |
| Accuracy | ~0.79 |
| F1-Score (Good Customers) | ~0.85 |
| F1-Score (Bad Customers) | ~0.63 |

The model demonstrated strong performance in identifying reliable customers while maintaining acceptable discrimination ability for risky profiles.

---

## Credit Scoring System

Predicted probabilities were transformed into a credit score ranging from 0 to 1000.

Customers were segmented into three risk categories:

| Risk Segment | Score Range |
|---|---|
| Low Risk | > 700 |
| Medium Risk | 500 – 700 |
| High Risk | < 500 |

This segmentation improves interpretability and supports operational decision-making processes.

---

## Dashboard

A Power BI dashboard was developed to visualize:
- customer risk segmentation
- average credit score
- default rate
- score distributions
- relationship between loan amount and credit score

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- Matplotlib
- Seaborn
- Power BI

---

## Future Improvements

Possible future developments include:

- Cross-validation techniques
- Ensemble models (Random Forest, XGBoost)
- Hyperparameter optimization
- Advanced outlier detection methods
- Explainable AI techniques
- Fairness and bias analysis

---

## Author

Francesco Lombardini

Statistics Graduate | Data Analysis | Machine Learning
