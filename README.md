Customer Churn Analysis
This project analyzes customer churn data to identify trends and factors influencing customer retention. It provides actionable insights using Python and data visualization techniques.

Dataset
The dataset contains 7,043 entries and 21 columns, including customer demographics, services used, and churn status. Key features include:

Tenure: Duration of service.
Contract: Type of subscription (e.g., month-to-month).
Payment Method: Modes like electronic check or mailed check.
Churn: Indicates whether a customer has churned (Yes/No).


Analysis Highlights
Key Findings:
Churn Rate:
26.54% of customers have churned.
Senior Citizens:
Higher churn rates observed among senior citizens.
Contract Type:
Month-to-month contracts are more prone to churn compared to annual contracts.
Tenure:
Customers with shorter tenure (1–2 months) are more likely to churn.
Payment Method:
Customers using electronic checks exhibit higher churn rates.


Visualizations:
Pie charts and count plots illustrate churn distribution and its relationship with customer attributes.
Stacked bar charts highlight the influence of contract type and senior citizen status on churn.
Tools and Libraries


Data Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Process Overview


Data Cleaning:
Replaced blank TotalCharges values with 0.
Converted SeniorCitizen values (0/1) to Yes/No for better readability.


Exploratory Data Analysis:
Visualized churn trends across various attributes.
Examined patterns in customer tenure and payment methods.


Insights:
Created actionable insights for strategies to reduce churn.
Visual Examples
Count of Customers by Contract
Churn by Senior Citizen Status

Conclusion
The analysis suggests focusing on improving retention strategies for short-tenure customers, offering incentives for long-term contracts, and reviewing electronic payment methods to address churn triggers.
