# Customer Segmentation Visualization & Advanced Analysis
## Project Overview
The project aims to analyze customer churn in a telecommunications company and develop predictive models to identify at-risk customers. 
The ultimate goal is to provide actionable insights and recommendations to reduce churn and improve customer retention.
By examining key factors such as tenure, contract type, payment method and monthly charges, we aimed to identify patterns influencing customer retention and provide actionable insights to reduce churn.

## Dataset Overview
The dataset contains customer information such as tenure, contract type, internet service, payment methods, and monthly charges.
The `Churn` column is the key variable, indicating whether a customer has left the service or not

## Process Overview
#### 1. Data Cleaning
- Removed missing values in the `TotalCharges` column.
- Converted `TotalCharges` from string to float.
- Standardized column names and removed unnecessary columns (`customerID`).
- Checked for duplicates and ensured data consistency.

#### 2. Exploratory Data Analysis(EDA)
- Analyzed correlation between tenure and total charges.
- Identified that **higher monthly charges are linked to higher churn rates**.
- Used various visualizations to explore churn rates based on contract type, internet service, and payment methods.

#### 3. Key Findings
- **Short-tenure customers (0-12 months) have the highest churn risk**.
- **Month-to-month contracts have the highest churn**, while long-term contracts reduce churn.
- **Customers using electronic check payment methods churn more frequently** than those on auto-pay.
- **Fiber Optic users churn more than DSL users**, possibly due to pricing.
- **Customers with partners and dependents churn less**, suggesting shared service commitments.

#### 4. Business Recommendations
- **Improve retention for new customers** through better onboarding and early-stage discounts.
- **Encourage long-term contracts** by offering loyalty discounts.
- **Promote auto-pay options** to reduce churn from electronic check users.
- **Leverage long-term customers** for referrals and upselling premium services.

#### Future Work
- Implement **predictive modeling** using machine learning to forecast churn risk.
- Conduct **sentiment analysis** on customer feedback to identify service pain points.

## **How to Use This Repository**
- The dataset is available in the repository.
- Run the provided Python scripts to reproduce the analysis and visualizations.
