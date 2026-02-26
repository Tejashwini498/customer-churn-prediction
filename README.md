# customer-churn-prediction
Customer churn prediction using machine learning (Random Forest &amp; Logistic Regression)
# Customer Churn Prediction

##  Project Overview
This project predicts customer churn for a telecom company using machine learning. The goal is to identify key drivers of churn and provide actionable recommendations to reduce it.

##  Dataset
- Source: [Kaggle Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Rows: 7,043 customers
- Features: 21 columns including tenure, monthly charges, contract type, etc.

##  Tools & Libraries
- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn (Logistic Regression, Random Forest)
- Google Colab

##  Key Steps
1. Exploratory Data Analysis (EDA) – visualizations to understand churn patterns.
2. Data preprocessing – one-hot encoding, scaling.
3. Model building – Logistic Regression and Random Forest.
4. Model evaluation – accuracy, confusion matrix, classification report.
5. Feature importance – identified top drivers of churn.

##  Key Insights
- **Tenure** is the strongest predictor – new customers are most likely to churn.
- **Monthly charges** above $70 significantly increase churn risk.
- **Month-to-month contracts** have much higher churn than long-term contracts.
- **Fiber optic internet** users churn more despite faster speeds.
- **Electronic check** payment method correlates with higher churn.

##  Business Recommendations
- Launch a loyalty program for new customers.
- Offer bundled services to reduce perceived monthly cost.
- Incentivize switching to annual contracts.
- Investigate fiber optic service issues.
- Promote auto-pay with a small discount.

## Files
- `Customer_Churn_Prediction.ipynb` – complete notebook with code and analysis.
- `feature_importance.png` – plot of top churn drivers (optional).

##  How to Run
1. Open the notebook in Google Colab.
2. Upload the dataset (or use the provided URL).
3. Run all cells.

