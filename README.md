# Telco Customer Churn Analysis

## Executive Summary
This project explores customer churn within a telecommunications provider’s dataset of 7,043 subscribers across 21 features. Through comprehensive exploratory data analysis (EDA), key drivers of churn—such as month-to-month contracts, early tenure, and electronic check payments—were identified, along with core retention factors like fixed-term agreements, long service duration, and bundled security/support offerings. Actionable insights guide targeted interventions to improve customer lifetime value and reduce attrition.

## Business Problem
Telecom companies face significant revenue loss when customers cancel services. With a churn rate of 26.54%, understanding which segments are most at risk and why is critical to designing retention programs that minimize churn related costs and maximize lifetime value.

## Methodology
The analysis began with ingestion of 7,043 customer records, followed by validation of data types and schema consistency. Key fields were cleaned by converting TotalCharges to float and encoding SeniorCitizen as an integer, ensuring no missing values or duplicates remained.

Descriptive statistics were generated to assess central tendencies and distributions for tenure, MonthlyCharges, and TotalCharges. These summaries provided context for the subsequent visualization choices.

A suite of univariate and bivariate visualizations—including count plots, histograms, pie charts, and stacked bar charts—was produced to explore relationships between churn and variables such as demographics, contract type, service usage, and payment method.

## Skills and Tools
- Python  
- Pandas for data manipulation  
- NumPy for numerical operations  
- Matplotlib for visualization  
- Seaborn for visualization  
- Jupyter Notebook for interactive analysis  
- Exploratory Data Analysis (EDA)  
- Data cleaning and type conversions  

## Results
- Overall churn rate: 26.54% (1,869 churners vs. 5,174 retained)  
- Demographics:  
  - Gender has negligible effect on churn  
  - Senior citizens churn at a 41.7% rate vs. 23.6% for non-seniors  
- Tenure:  
  - Highest churn within first 3 months  
  - Strong loyalty after 60+ months  
- Contract type:  
  - Month-to-month contracts drive 88.6% of churners  
  - One- and two-year terms show markedly lower attrition  
- Services and support:  
  - OnlineSecurity and TechSupport reduce churn  
  - Fiber optic users churn more than DSL customers  
- Payment behavior:  
  - Electronic check users churn most frequently  
  - Automatic payments (bank transfer, credit card) correlate with strong retention  

## Business Recommendations
- Promote fixed-term contracts  
  Incentivize month-to-month customers to upgrade to one- or two-year plans.

- Strengthen early-stage engagement  
  Implement welcome flows, onboarding calls, and value-driven nudges during the first 90 days.

- Bundle retention-friendly services  
  Offer discounts on OnlineSecurity and TechSupport packages.

- Encourage automatic payments  
  Launch campaigns to move electronic check users to bank transfer or credit card billing.

- Target senior customers  
  Provide tailored support, proactive outreach, and specially designed plans for senior segments.



