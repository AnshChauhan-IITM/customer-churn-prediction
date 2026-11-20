# Customer Churn Prediction

A Machine Learning project focused on identifying customers who are likely to leave a telecommunications service and developing data-driven customer retention strategies.

## Project Overview

Customer churn is a major challenge for subscription-based businesses. Losing customers affects recurring revenue and increases customer acquisition costs.

This project analyses customer behaviour, builds machine learning classification models to predict churn, and uses model explainability techniques to generate actionable retention insights.

## Business Objectives

- Understand customer churn patterns.
- Perform exploratory data analysis (EDA).
- Identify important customer features associated with churn.
- Build and compare machine learning models.
- Evaluate model performance using classification metrics.
- Analyse classification thresholds and business costs.
- Interpret model predictions using SHAP.
- Develop customer retention recommendations.

## Dataset

**Dataset:** Telco Customer Churn

**File:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`

The dataset contains customer information, service subscriptions, account details and churn status.

## Tools & Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- SHAP
- Jupyter Notebook

## Project Workflow

### 1. Data Understanding and Cleaning
- Dataset inspection and structure analysis.
- Missing value and duplicate checks.
- Data type handling and preprocessing.
- Feature preparation.

### 2. Exploratory Data Analysis
- Customer churn distribution.
- Churn patterns across customer features.
- Service, contract and payment-related analysis.
- Identification of important trends.

### 3. Feature Engineering and Preprocessing
- Encoding categorical variables.
- Preparing features for machine learning.
- Training and testing data separation.

### 4. Machine Learning Models

The following classification models were trained and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Tuned Random Forest

### 5. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- PR-AUC
- Confusion Matrix

#### Model Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.8003 | 0.6491 | 0.5544 | 0.5980 |
| Decision Tree | 0.7249 | 0.4866 | 0.4801 | 0.4833 |
| Random Forest | 0.7775 | 0.6074 | 0.4801 | 0.5363 |
| Tuned Random Forest | 0.7896 | 0.6328 | 0.5119 | 0.5660 |

Logistic Regression achieved the highest F1 Score among the compared models at the default classification threshold.

### 6. Threshold and Business Cost Analysis

- Evaluated multiple classification thresholds.
- Analysed false positives and false negatives.
- Compared recall and precision trade-offs.
- Used hypothetical business costs to understand retention campaign decisions.

### 7. Model Explainability using SHAP

SHAP was used to interpret model predictions and understand which features contributed to churn-risk predictions.

### 8. Customer Risk Segmentation

Customers were grouped into risk categories to support prioritisation of retention efforts.

## Business Recommendations

- Prioritise high-risk customers for proactive retention campaigns.
- Develop targeted offers for customers identified as vulnerable to churn.
- Review contract and service-related customer patterns.
- Monitor retention campaign effectiveness.
- Evaluate business outcomes using customer retention, churn reduction and campaign ROI.

## Key Learning Outcomes

- End-to-end machine learning workflow.
- Exploratory data analysis and feature engineering.
- Classification model comparison and evaluation.
- Threshold optimisation based on business costs.
- Model explainability using SHAP.
- Translating analytical results into business recommendations.

## Repository Structure

```text
customer-churn-prediction/
│
├── notebooks/
│   └── Customer_Churn_Analysis.ipynb
│
├── README.md
└── ...
```

## Project Notebook

[View the Complete Customer Churn Analysis Notebook](notebooks/Customer_Churn_Analysis.ipynb)

---

**Project Focus:** Machine Learning | Customer Analytics | Churn Prediction | Business Intelligence

**Status:** Analysis and model development completed. Repository documentation and organisation are being finalised.
