# Creating the README.md file content for the churn analysis project


# Churn Analysis Project for ABC Bank

## Executive Summary
This project analyzes customer churn at ABC Bank to identify key factors influencing churn and develop actionable insights for retention strategies. Leveraging tools like Excel, Power BI, and GitHub, we provide an in-depth exploration of customer demographics, behavior, and satisfaction to drive business improvements.

---

## Project Objectives
1. Understand factors contributing to customer churn.
2. Segment customers by churn risk to prioritize retention efforts.
3. Develop data-driven insights to design loyalty programs and improve customer satisfaction.

---

## Dataset Overview
- **Source**: Internal bank data
- **Key Columns**:
  - **CreditScore**: Indicates financial reliability.
  - **Geography**: Customer location.
  - **Gender**: Demographic information.
  - **Age**: Indicates life stage.
  - **Tenure**: Years as a bank client.
  - **Balance**: Financial standing in accounts.
  - **NumOfProducts**: Products purchased through the bank.
  - **HasCrCard**: Credit card ownership status.
  - **IsActiveMember**: Activity status.
  - **Satisfaction Score**: Feedback on service.
  - **Exited**: Churn status.

---

## Tools and Technologies
1. **Excel**: Data cleaning and preliminary exploration.
2. **Power BI**: Interactive dashboard creation and data visualization.
3. **GitHub**: Version control and project collaboration.

---

## Key Performance Indicators (KPIs)
1. **Overall Churn Rate**
2. **Number of Churned Customers**
3. **High-Risk Customers**
4. **Revenue at Risk**
5. **Average Satisfaction Score**
6. **Complaints Logged**
7. **Inactive Customers**

---
## Customer Risk Score Logic Used

**High Risk**:
A customer is considered "High Risk" if any of the following conditions are true:


Their Credit Score is less than 400.
Their Balance is less than 10,000.
They are not an active member (i.e., IsActiveMember = 0).


**Medium Risk**:
A customer is classified as "Medium Risk" if:
Their Credit Score is between 400 and 699 (inclusive).
OR their Balance is between 10,000 and 49,999 (inclusive).

**Low Risk**:
Any customer who does not fall into the above two categories is considered "Low Risk."

---
## Dashboard Features
- **Customer Distribution by Risk Level**: High, Medium, Low.
- **Churn Analysis by Geography**: Regional trends and hotspots.
- **Behavioral Insights**: Impact of activity levels, products, and card types.
- **Demographics Breakdown**: Age, gender, and salary trends.
- **Revenue Impact Assessment**: Financial losses due to churn.
- **Customer Feedback Analysis**: Satisfaction scores and complaint patterns.

---

## Analysis Process
1. **Data Cleaning**: Ensured consistency and handled missing values.
2. **Risk Segmentation**: Classified customers into High, Medium, and Low churn risk levels.
3. **Churn Drivers Identification**: Analyzed correlations between churn and features like CreditScore, Tenure, and Satisfaction Score.
4. **Visualization**: Built interactive charts for actionable insights.

---
## Key Insights
### 1. **Customer Churn Risk**: 

- 67% of customers fall under the "High Risk" category, indicating a significant portion of the customer base is prone to churn. Medium-risk customers constitute 22%, and only 10% are at low risk.

### 2. **Churn by Geography**: 
- Spain has lowest number of churns while France (811) and Germany (814) being almost equal contributors.

### 3. **Churn by Risk Level**: 
- High-risk customers account for 67% of churn (1,487 churned, 22.11% churn rate).
- Medium-risk and low-risk customers churn at similar rates (~16.5%) but contribute less to overall churn volumes.

### 4. **Churn by Gender**:
- Male customers (56%) churn more than female customers (44%).
- This suggests a potential need for gender-specific customer engagement strategies.

### 5. **Churn by Credit Score**:
- Customers with "Good" (705) and "Fair" (685) credit scores churn more frequently.
- "Excellent" score customers (128 churned) have the lowest churn, indicating high retention in this segment.

### 6. **Churn by Number of Products**:
- A staggering 69% of churned customers only have one product.
- Customers with more products (3 or 4) are far less likely to churn, indicating that cross-selling additional products can improve retention.

### 7. **Churn by Age Bracket**:
- The 45-59 age group has the highest churn rate (49.74%).
- 60+ customers also have significant churn rates (28.11%), while younger age groups churn less.

### 8. **Churn by Tenure and Complaints**:
- Customers with a tenure of 2-4 years (617 churned) have the highest churn.
- Churn steadily declines with tenure, but customer satisfaction also drops over time.
- Complaints increase as tenure progresses, indicating dissatisfaction buildup.
---
## Business Recommendations

### 1. **Target High-Risk Customers**
   - **Action Plan**: Design loyalty programs and personalized offers for high-risk customers to prevent churn.
   - **Proactive Engagement**: Implement proactive customer service outreach for early engagement and retention.
   
### 2. **Address Regional Churn**
   - **Survey Implementation**: Conduct surveys and focus groups in high-churn regions (Germany & France) to understand key churn drivers. Analyze what's working in Spain (drives least number of churns).

### 3. **Encourage Multi-Product Adoption**
   - **Bundled Product Offerings**: Develop and promote bundled product offerings to encourage customers to add more products.
   
### 4. **Engage Mid-Tenure Customers**
   - **Rewards Programs**: Introduce loyalty rewards and recognition programs for customers in the 2-4 year tenure range to reduce churn.
   - **Complaint Resolution**: Proactively address and resolve customer complaints to improve satisfaction and retention.
   
### 5. **Improve Credit Score Retention Strategies**
   - **Tailored Financial Products**: Offer personalized financial products and benefits for customers with "Good" and "Fair" credit scores.
   - **Exclusive Benefits for High-Credit-Score Customers**: Provide special offers and benefits to maintain the loyalty of customers with high credit scores.
   
### 6. **Age-Specific Interventions**
   - **Targeted Campaigns**: Develop campaigns specifically focused on the 45-59 and 60+ age groups, addressing their unique needs and concerns to increase retention.
   
### 7. **Enhance Customer Satisfaction**
   - **Complaint Monitoring**: Monitor and address customer complaints systematically, especially among long-tenure customers.
   - **Customer Support**: Enhance customer support channels and feedback mechanisms to address dissatisfaction early.

---

## Future Scope
1. Incorporate temporal data to analyze churn trends over time.
2. Integrate predictive models to forecast future churn risks.
3. Expand segmentation with additional customer attributes.

---


