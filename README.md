Customer Churn Analysis System
Project Overview

Customer churn is one of the most critical challenges faced by businesses, especially in banking, telecommunications, and subscription-based services. Customer churn refers to customers discontinuing their relationship with a company.

This project focuses on analyzing customer data to identify patterns and factors associated with customer churn using Exploratory Data Analysis (EDA). The analysis helps businesses understand customer behavior and develop retention strategies to reduce customer loss.

Objectives
Generate and analyze customer data.
Perform data cleaning and preprocessing.
Explore customer demographics and account information.
Identify factors influencing customer churn.
Visualize relationships between customer attributes and churn.
Generate business insights for customer retention.
Dataset Information

The dataset contains 100,000 customer records with the following attributes:

Column	Description
Customer_ID	Unique customer identifier
Age	Customer age
Gender	Male or Female
Tenure	Years with the company
Balance	Account balance
CreditScore	Customer credit score
EstimatedSalary	Estimated annual salary
NumOfProducts	Number of products used
IsActiveMember	Active membership status
Churn	Target variable (0 = No Churn, 1 = Churn)
Technologies Used
Python
Google Colab
Pandas
NumPy
Matplotlib
Seaborn
Project Workflow
1. Data Generation

A synthetic dataset containing 100,000 customer records was generated using NumPy.

2. Data Preprocessing
Checked dataset structure
Verified missing values
Converted categorical variables into numerical format
Removed inconsistencies
3. Exploratory Data Analysis (EDA)

The following analyses were performed:

Churn Distribution Analysis
Number of churned customers
Number of retained customers
Demographic Analysis
Age vs Churn
Gender vs Churn
Customer Activity Analysis
Active Member vs Churn
Financial Analysis
Balance vs Churn
Credit Score vs Churn
Tenure vs Churn
Correlation Analysis
Heatmap visualization
Feature relationship identification
Visualizations Included
Count Plots
Churn Distribution
Gender vs Churn
Active Member vs Churn
Box Plots
Age vs Churn
Balance vs Churn
Credit Score vs Churn
Tenure vs Churn
Heatmap
Correlation between numerical features

Key Findings
Customer Churn Statistics
Total Customers: 100,000
Churn Customers: 42,450
Churn Rate: 42.45%
Major Factors Affecting Churn
Low Credit Score
Customers with lower credit scores showed higher churn probability.
Low Tenure
New customers were more likely to churn.
Inactive Membership
Inactive members had significantly higher churn rates.
High Balance with Inactivity
Customers maintaining high balances but remaining inactive were more likely to leave.

Business Recommendations
Improve Customer Engagement
Launch loyalty programs.
Increase customer interaction.

Retain New Customers
Offer onboarding support.
Provide early-stage incentives.

Monitor High-Risk Customers
Track customers with low credit scores.
Identify inactive customers for targeted campaigns.

Personalized Marketing
Create customized offers based on customer behavior.

Project Structure
Customer-Churn-Analysis/
│
├── churn_analysis.ipynb
├── README.md
├── dataset.csv
├── images/
│   ├── churn_distribution.png
│   ├── age_vs_churn.png
│   ├── balance_vs_churn.png
│   ├── creditscore_vs_churn.png
│   └── heatmap.png
│
└── requirements.txt
Future Enhancements
Implement Machine Learning models:
Logistic Regression
Random Forest
Decision Tree
XGBoost
Build a Customer Churn Prediction System.
Deploy as a Web Application using Flask or Streamlit.
Integrate real-world customer datasets.
Conclusion

This project successfully analyzed customer churn patterns using Exploratory Data Analysis techniques. The findings indicate that customer activity status, credit score, tenure, and account balance play important roles in predicting churn behavior. The insights obtained can help businesses develop effective customer retention strategies and improve long-term profitability.

<img width="601" height="463" alt="image" src="https://github.com/user-attachments/assets/ed7bf18e-5b7a-4f57-bf34-0704f4de75a3" />
<img width="572" height="463" alt="image" src="https://github.com/user-attachments/assets/08a71c97-7d14-41a7-b85c-9521eac7dc2b" />
<img width="601" height="463" alt="image" src="https://github.com/user-attachments/assets/49c1f17b-4641-44c8-b28f-6ad0741eacbb" />
<img width="601" height="463" alt="image" src="https://github.com/user-attachments/assets/0fc99d00-6dc0-4b74-9501-ec68a4d0d511" />
<img width="610" height="463" alt="image" src="https://github.com/user-attachments/assets/4092e7e8-3add-4763-9171-6c8accac63a1" />
<img width="581" height="463" alt="image" src="https://github.com/user-attachments/assets/5fce9fff-38a2-45d9-8831-5d723288c64a" />
<img width="572" height="463" alt="image" src="https://github.com/user-attachments/assets/c4a95b89-94a3-4e3f-81da-05b259c094c7" />
<img width="890" height="643" alt="image" src="https://github.com/user-attachments/assets/548ceb27-4a5d-45c5-89aa-f55cb6c2ee9d" />







