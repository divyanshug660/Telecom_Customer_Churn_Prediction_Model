# **Telecom_Customer_Churn_Prediction_Model**

This project focuses on customer churn analysis and prediction using a Random Forest model. The data used includes information about customer demographics, services, contracts, payment methods, and a lot more. The analysis was conducted using tools such as Google Colab, Numpy, Pandas, Scikit-learn, Seaborn, and Plotly for visualization.

## **Tools_And_Techniques**

**Data Cleaning:** 
Removal of missing alues and irrelevant features.

**Exploratory Data Analysis (EDA):** Investigation of patterns and trends in the data.

**Interactive Visualization:** 
Created interactive visualizations to represent key trends.

**Random Forest Model:** 
Used for churn prediction.

**SMOTE (Synthetic Minority Oversampling Technique):** 
Applied to balance the dataset by oversampling the minority class (churned customers).

**Performance Evaluation:** 
Achieved an accuracy of 83.01%.

## **Key Inferences**
**Churn Rate:**
26.6% of customers switched from the current firm to another.

**Gender Demographics:**
49.5% were female, and 50.5% were male.

**Contract Type and Churn:**
75% of customers with month-to-month contracts churned, while only 13% with one-year contracts and 3% with two-year contracts churned.

**Payment Method:**
Customers who used Electronic Check as a payment method exhibited the highest churn rate. Customers who used Credit-Card Automatic Transfer, Bank Automatic Transfer, and Mailed Check were less likely to churn.

**Service Type and Churn:**
Fiber Optic service customers had a higher churn rate, suggesting potential dissatisfaction with the service. DSL service users had a lower churn rate.

**Dependents:**
Customers without dependents were more likely to churn compared to those with dependents.

**Partners and Churn:**
Surprisingly, customers with partners were more likely to churn.

**Online Security:**
The absence of online security services increased the likelihood of churn.

**Paperless Billing:**
Customers who used paperless billing were more likely to churn.

**Technical Support:**
Lack of tech support contributed to a higher churn rate.

**Phone Service:**
A small fraction of customers without phone services were more likely to churn.



## **Conclusion**

The analysis shows that factors such as contract type, payment method, service type, and support services significantly influence customer churn. The insights from this analysis can be used by telecom companies to improve retention strategies by addressing the issues found, particularly with Fiber Optic service and the absence of online security and tech support.

## **Model Performance**

The Random Forest model achieved an accuracy of 83.01%, which is a solid indicator of the model's reliability in predicting customer churn. SMOTE was applied to balance the class distribution, ensuring fairer predictions for the minority class (churned customers).
