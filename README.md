# Tele_Customer_Churn

![customer_retention_1](https://github.com/user-attachments/assets/7e36ee84-ac7b-44fd-b2a7-b552954d32d4)



Churn prediction means detecting which customers are likely to cancel a subscription to a service based on how they use the service. It is a critical prediction for many businesses because acquiring new clients often costs more than retaining existing ones. Once you can identify those customers that are at risk of cancelling, you should know exactly what marketing action to take for each individual customer to maximise the chances that the customer will remain.



## 📌 Why is it so important?

Customer churn is a common problem across businesses in many sectors. If you want to grow as a company, you have to invest in acquiring new clients. Every time a client leaves, it represents a significant investment lost. Both time and effort need to be channelled into replacing them. Being able to predict when a client is likely to leave, and offer them incentives to stay, can offer huge savings to a business.


## 📂 Dataset

**Direct Download**

<a href="https://github.com/PrakashRanjanShrivastava/Tele_Customer_Churn/blob/main/Data/Telco-Customer-Churn.csv.csv">Tele_customer_Churn_data</a>

- Source: [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)

- Size: ~7K records

- Features: Gender, Tenure, Monthly Charges, Total Charges, Service Subscriptions, Churn (target)


## 📊 About This Project

- **Total Monthly Charges**: ~$16,056,169
- **Revenue Loss from Churn**: ~$2,862,927 (~18%)
- **Total Customers**: ~7043
- **Churned Customers**: ~1869 (~27%)

The goal is to predict which customers are most likely to churn so that proactive retention strategies can be implemented.

## 🧪 Project Workflow

1. Data Analysis (EDA)
2. Data Preprocessing
3. Feature Engineering
4. Feature Selection (SelectKBest)
5. ML Model Training
6. Hyperparameter Tuning (RandomSearchCV)
7. Model Deployment (Pickle)

## 🔍 Insights

- Churn is more likely among short-tenure users and those on month-to-month contracts.
- Higher churn observed among senior citizens and customers using electronic payment methods.
- High revenue loss from churning customers makes this prediction essential.

## ✅ Recommendations

- Incentivize long-term contracts.
- Provide offers and engagement to new customers (low tenure).
- Improve support for senior citizens and high-paying customers.
- Launch proactive retention campaigns based on churn prediction scores.

## 🛠 Tools Used

- Python
- Pandas
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

**🚀 This project helps telecom providers make data-driven decisions to reduce churn and increase profitability.**

