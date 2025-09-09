# Telco Customer Churn Analysis

## **Executive Summary**
This project explores customer churn within a telecommunications provider’s dataset of 7,043 subscribers across 21 features. Through comprehensive exploratory data analysis (EDA), we identify key drivers of churn—such as month-to-month contracts, early tenure, and electronic check payments—and core retention factors like fixed-term agreements, long service duration, and bundled security/support offerings. Actionable insights guide targeted interventions to improve customer lifetime value and reduce attrition.

## **Business Problem**
Telecom companies face significant revenue loss when customers cancel services. With a churn rate of 26.54%, understanding which segments are most at risk—and why—is critical to designing retention programs that minimize churn-related costs and maximize lifetime value.

## **Methodology**
We began by ingesting the raw dataset of 7,043 customer records, validating data types, and sampling entries to confirm schema accuracy. After initial inspection, we corrected key fields—transforming `TotalCharges` to float and encoding `SeniorCitizen` as an integer—and verified that no nulls or duplicates remained.

Next, we generated descriptive summaries to understand central tendencies for tenure, monthly charges, and total charges. This statistical profiling guided our choice of visualizations to highlight distributional insights across customer segments.

Finally, we produced a suite of univariate and bivariate plots—including count charts, histograms, and stacked bars—to examine relationships between churn and demographic, contractual, service, and payment variables. These visual analyses revealed high-leverage factors for targeted retention strategies.

## **Skills and Tools**
- Python  
- Pandas for data manipulation  
- NumPy for numerical operations  
- Matplotlib for visualization  
- Seaborn for visualization  
- Jupyter Notebook for interactive analysis  
- Exploratory Data Analysis (EDA)  
- Data cleaning and type conversions  

## **Results**
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

## **Business Recommendations**
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
