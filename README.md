# Customer Churn Prediction Project

##  Project Overview

This project focuses on analyzing customer behavior to predict churn using supervised machine learning models. The goal is to identify high-risk customers and provide data-driven strategies to reduce churn and increase customer retention.

The dataset used contains demographic and service-related information about telecom customers, and the target variable indicates whether a customer has churned or not.

---

##  Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab


##  Machine Learning Models

The following models were trained and evaluated:
- **Logistic Regression** *(Best overall performer)*
- **Random Forest Classifier**
- **Support Vector Machine**
- **Decision Tree**

### Evaluation Metrics:
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- ROC Curve & AUC Score


##  Key Findings

- **Logistic Regression** had the highest performance, with strong precision for non-churned customers and moderate performance for churned customers.
- **Random Forest** also performed well and provided valuable feature importance scores.

### Top Features Influencing Churn:
- `InternetService_Fiber optic` (highly correlated with churn)
- `MonthlyCharges`, `TotalCharges`, and `Tenure`
- `PaymentMethod_Electronic check`
- Optional services like StreamingTV and PhoneService

## Strategic Recommendations

- **Target new customers** with loyalty offers
- **Improve fiber optic service** or provide affordable alternatives
- **Promote long-term contracts** through incentives
- **Optimize the payment experience** (shift from electronic checks)
- **Use churn scores** for proactive retention campaigns

See [Strategic Recommendations section]in the notebook for more detail.



