## View Notebook
[Open in NBViewer](https://nbviewer.org/github/raaghul07/telecom-customer-churn-prediction/blob/main/Telecom_Customer_Churn_Prediction.ipynb)

# 📉 Telecom Customer Churn Prediction

Machine learning classification project to predict which telecom customers are likely to churn, using exploratory data analysis and two ML models.

## 📊 Project Overview
This project analyzes telecom customer behavior to identify churn risk factors and builds classification models to predict customer churn with high accuracy.

## 📁 Dataset
- **Source:** [Telecom Customer Churn Dataset - Kaggle](https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets)
- **Size:** 3,333 customer records, 11 features
- **Target:** Churn (0 = Retained, 1 = Churned)

## 🔍 Key Findings
- DayMins and MonthlyCharge are the strongest churn predictors
- Customers with 4+ service calls churn at a significantly higher rate
- Customers without contract renewal are at much higher churn risk
- DataPlan has the least impact on churn likelihood

## 🤖 Model Performance
| Metric | Logistic Regression | Random Forest |
|--------|-------------------|---------------|
| Accuracy | 86% | 93% |
| ROC-AUC | 0.831 | 0.921 |
| Churn Recall | 0.18 | 0.61 |
| Churn F1 | 0.28 | 0.72 |

**Random Forest is the recommended model for production use.**

## 💡 Business Insight
Telecom companies should flag customers with high monthly charges, frequent support calls, and no contract renewal as highest priority churn risks for retention campaigns.

## 🛠️ Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Logistic Regression, Random Forest, ROC-AUC)

## 📓 Notebook
See `Telecom_Customer_Churn_Prediction.ipynb` for the full analysis.
