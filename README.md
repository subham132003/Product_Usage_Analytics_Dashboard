Product_Usage_Analytics_Dashboard
 Project Overview
This project analyzes   user activity and product usage patterns   to generate insights on engagement and churn.  
The dataset simulates 500 users with details like number of sessions, active days, features used, session time, and churn status.  

The goal is to:
- Understand how users interact with the product.
- Identify factors influencing churn.
- Provide business stakeholders with a dashboard for decision-making.

---

Dataset
  File:   `product_usage_data.csv`  

| user_id | signup_date | active_days | sessions | features_used | avg_session_time_min | churned |
|---------|-------------|-------------|----------|---------------|-----------------------|---------|
| 1       | 2023-01-01  | 7           | 70       | 6             | 5                     | 0       |
| 2       | 2023-01-02  | 20          | 36       | 7             | 30                    | 0       |
| 3       | 2023-01-03  | 29          | 91       | 8             | 23                    | 0       |
| 4       | 2023-01-04  | 15          | 67       | 2             | 26                    | 0       |
| 5       | 2023-01-05  | 11          | 90       | 8             | 14                    | 1       |

-   churned = 0   → Active user  
-   churned = 1   → User has churned  

---

 Tools & Technologies
-   Python:   pandas, numpy, matplotlib, seaborn  
-   SQL:   for querying and aggregations  
-   Power BI / Tableau:   dashboard creation  
-   Excel:   quick analysis and reporting  

---

 Key Analysis
1.   Engagement Metrics  
   - Average sessions per user
   - Features used distribution
   - Average session time

2.   Churn Analysis  
   - Active vs. churned users
   - Relationship between active days, features used, and churn

3.   Dashboard KPIs  
   - Total Active Users  
   - Average Session Time  
   - Feature Usage per User  
   - Churn Percentage  

--- Dashboard (Power BI / Tableau)
The dashboard provides:
-   Line Chart   → User activity trend over time  
-   Bar Chart   → Features used distribution  
-   Pie Chart   → Churn vs Active users  
-   KPIs   → Active users, Avg. session time, Churn %  

 (Add screenshot here once dashboard is ready)   

---

 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/subham132003/Product_Usage_Analytics_Dashboard
