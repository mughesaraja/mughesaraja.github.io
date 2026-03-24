**Customer Churn Analysis & Prediction**
**Overview**

This project explores customer churn behaviour using a real-world telecom dataset.
The goal was to identify key factors influencing churn and build a machine learning model to predict customers at risk of leaving.

**Objectives**
Clean and preprocess raw customer data
Perform exploratory data analysis (EDA)
Identify key drivers of churn
Build a predictive model using Logistic Regression
Generate churn probabilities for each customer
Visualise insights using Power BI

**Tools & Technologies**
Python (Google Colab)
Pandas & NumPy
Scikit-learn
Power BI

**Dataset**
Telco Customer Churn Dataset
Includes customer demographics, contract details, billing information, and churn status

**Data Cleaning & Preparation**
Removed irrelevant columns (e.g. location data, IDs)
Converted Total Charges to numeric format
Handled missing values
Encoded categorical variables using one-hot encoding

**Model Development**
Model used: Logistic Regression
Train/test split: 80/20
Features included:
Tenure Months
Monthly Charges
Total Charges
Contract Type
Payment Method
Paperless Billing

**Results**
Model Accuracy: ~79%
Strong performance in predicting non-churn customers
Moderate performance in identifying churn customers

**Key Insights**
Customers on month-to-month contracts have higher churn risk
Certain payment methods are associated with higher churn
Higher monthly charges can correlate with increased churn probability
Churn risk can be segmented into High / Medium / Low categories

**Power BI Dashboard**
An interactive dashboard was created to:

Visualise churn probability by contract type
Identify high-risk customer segments
Explore trends across payment methods and tenure
Highlight customers with high churn probability

**Future Improvements**
Apply advanced models (Random Forest, XGBoost)
Improve recall for churn prediction
Perform feature importance analysis
Deploy as a simple web app or dashboard

**Project Structure**
customer_churn_analysis.ipynb → Data cleaning, modelling, and analysis
churn_with_probabilities.csv → Final dataset with predictions
Power BI dashboard → Visual insights

**Conclusion**
This project demonstrates an end-to-end data analysis workflow, from raw data to actionable business insights, combining Python and Power BI to support data-driven decision making.

**Business Recommendations**
Based on the analysis and model predictions, the following actions could help reduce customer churn:

**1. Target High-Risk Customers**
Customers with a churn probability above 70% should be prioritised for retention strategies such as:
Personalised offers or discounts
Proactive customer support outreach
Contract upgrade incentives

***2. Encourage Long-Term Contracts**
Customers on month-to-month contracts showed higher churn risk.
Offer incentives to move customers onto 1-year or 2-year plans
Provide pricing benefits for longer commitments

**3. Optimise Payment Methods**
Certain payment methods (e.g. electronic check) are associated with higher churn.
Encourage customers to switch to automatic payments
Offer small discounts for auto-pay adoption

**4. Monitor High Monthly Charges**
Customers with higher monthly charges may be more likely to churn.
Introduce loyalty discounts for long-term customers
Offer bundled services to increase perceived value

**5. Implement a Churn Monitoring System**
Use the model to regularly score customers
Create a live dashboard (Power BI) for tracking churn risk
Enable customer service teams to act on real-time insights

**Business Impact**
Implementing these strategies could:
Reduce customer churn rate
Increase customer lifetime value (CLTV)
Improve customer satisfaction and retention
Support more data-driven decision making


