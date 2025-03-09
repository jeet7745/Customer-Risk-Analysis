# 1. Overview of the Report

This Power BI report provides an in-depth analysis of customer churn, identifying key factors that contribute to customer attrition. The report helps businesses assess risk, understand churn patterns, and optimize strategies to retain customers.

# 2. Key Performance Indicators (KPIs) & DAX Measures

#### 1. Churn Rate

- Formula (DAX):

Churn Rate = DIVIDE(COUNTROWS(FILTER(CustomerData, CustomerData[Churn] = "Yes")), COUNTROWS(CustomerData)) * 100

- Purpose: Measures the percentage of customers who have left the service.

- Visualization: KPI Card, Pie Chart.

#### 2. Churn by Internet Service Type

- Analysis: Customers with Fiber optic service have the highest churn rate (43.96%).

- DSL and No Internet Service customers have lower churn rates.

- Purpose: Helps understand the impact of internet service type on churn.

- Visualization: Bar Chart.

#### 3. Churn by Contract Type

- Analysis: Month-to-month contracts have the highest churn rate (43%).

One-year and two-year contracts show significantly lower churn rates (11% and 3%, respectively).

- Purpose: Identifies contract types that are more likely to retain customers.

#### 4. Churn by Payment Method

- Analysis: Electronic check users have the highest churn rate (45%).

Customers using automatic bank transfers and credit cards show lower churn rates (17% and 15%).

- Purpose: Assesses how payment methods influence customer retention.

- Visualization: Column Chart.

#### 5. Years of Contract vs. Churn Rate

- Analysis: Customers with less than 1 year of contract have the highest churn rate (48%).

Longer contract durations show a decreasing churn trend.

- Purpose: Provides insights into how contract tenure affects churn risk.

#### 6. Admin & Tech Support Tickets

- Analysis: 3,632 Admin Tickets and 2,955 Tech Tickets were raised.

High churn may correlate with unresolved technical and administrative issues.

- Purpose: Understands customer dissatisfaction sources.

- Visualization: KPI Cards.

# 3. Report Structure in Power BI

Dashboard Overview: Displays key churn-related KPIs.

Churn Breakdown: Shows customer churn trends based on contract type, payment method, and internet service.

Customer Tenure Analysis: Highlights how customer longevity impacts churn.

Support Tickets & Churn: Examines the role of support issues in customer attrition.

# 4. Insights & Recommendations

Encourage Long-Term Contracts to reduce churn.

Improve Customer Support to lower churn linked to admin and tech issues.

Analyze High-Risk Payment Methods and promote more stable payment options.

Optimize Internet Service Plans to enhance customer satisfaction.

# 5. Technical Skills Applied:

Power BI: Data modeling, interactive visualizations, report automation.

DAX: Advanced calculations, aggregations, filtering, and measures.

Power Query: Data transformation, cleaning, and relationship management.
