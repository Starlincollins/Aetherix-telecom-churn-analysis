# Aetherix-telecom-churn-analysis
Aetherix Telecom faced customer retention challenges, requiring an exploratory analysis to identify key drivers of customer attrition and provide data-backed strategies to improve early customer retention.

Business Problem and Context
Aetherix Telecom faced customer retention challenges, requiring an exploratory analysis to identify key drivers of customer attrition and provide data-backed strategies to improve early customer retention. The dataset exhibited significant class imbalance (~26.54% churn rate).
Tools and Methodology
Languages and Libraries: Python (Pandas, NumPy, Seaborn, Matplotlib) for data cleaning, transformation, and EDA.
Business Intelligence: Power BI for interactive data modeling, custom DAX measures, and executive KPI dashboard creation.
Data Wrangling: Addressed missing data (0.16% dropped), converted data types, and engineered categorical tenure groups (1–12, 13–24, 25–36, 37–48, 49–60, 61–72 months).
 
Key Findings and Analytical Insights
Critical Tenure Window: 25% of churned customers leave within their first 9 months. Churn heavily spikes in the 1–12 month tenure group.
High-Value Attrition: Customers paying above the mean monthly charge ($65/mo) churn at significantly higher rates, preventing high-value customers from accumulating long-term total charges.
Contract and Payment Friction: Month-to-month contract holders represent the vast majority of churned users. Among payment channels, customers using electronic checks show the highest churn rate.
Service Dissatisfaction: Fiber optic internet subscribers experience disproportionately high churn compared to DSL users. Lack of value-added add-ons (Online Security, Online Backup, Device Protection, and Tech Support) strongly correlates with customer departure.
 
Strategic Recommendations
Early Onboarding and Retention: Deploy targeted retention campaigns specifically for customers within their first 12 months.
Contract Migration: Offer incentives to migrate high-value month-to-month subscribers toward longer-term 1-year or 2-year contracts.
Fiber Optic Quality Assurance: Conduct a service quality review for Fiber Optic offerings to address underlying subscriber dissatisfaction.
Service Bundling: Create discounted bundles that include Online Security and Device Protection to increase customer stickiness.
