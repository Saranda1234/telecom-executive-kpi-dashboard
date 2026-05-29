# Telecom Executive KPI Dashboard

## Project Overview
Executive-level KPI dashboard built using Apache Superset, providing
a comprehensive view of telecom business performance across revenue,
customer activity, churn, and call center metrics for **7,043 active customers**.

## Dashboard Preview
<img width="943" height="465" alt="image" src="https://github.com/user-attachments/assets/0fc4a8c7-1bb3-4539-ae24-671dee6e0db0" />

<img width="931" height="242" alt="image" src="https://github.com/user-attachments/assets/32fd6792-4076-443a-9540-c32bcfb49aeb" />



## Key Metrics
| Metric | Value |
|--------|-------|
| Total Revenue | 16.1M |
| Active Customers | 7,043 |
| Churn Rate % | 26.5% |
| Avg Daily Call Minutes | 577.76 |

## Charts & Analysis

### 1. KPI Overview
<img width="910" height="128" alt="image" src="https://github.com/user-attachments/assets/bb57a7b0-e08e-47dd-ad75-0003e27fe073" />

High-level executive snapshot showing total revenue of 16.1M,
7,043 active customers, 26.5% churn rate, and average daily
call minutes of 577.76.

### 2. Revenue by Contract Type
<img width="459" height="218" alt="image" src="https://github.com/user-attachments/assets/d5faa8a6-fb48-4a5b-bb66-1a3ca597a187" />

Bar chart comparing revenue generated across Month-to-month,
One year, and Two year contracts. Month-to-month contracts
generate the highest revenue volume but also carry the highest churn risk.

### 3. Churn by Internet Service
<img width="452" height="220" alt="image" src="https://github.com/user-attachments/assets/745d7d5f-b235-4567-9399-d993dd9d6ebf" />

Donut chart showing churn distribution across internet service types:
- Fiber optic: 43.96%
- DSL: 34.37%
- No internet service: 21.67%

Fiber optic subscribers represent the highest churn segment,
signaling a need for targeted retention strategies.

### 4. Daily vs Evening Call Minutes
<img width="461" height="241" alt="image" src="https://github.com/user-attachments/assets/74368211-4a9d-4b8f-b12e-78dc25b37fbc" />

Line chart tracking the sum of daily call minutes across the customer base,
revealing usage patterns and peak activity periods.

### 5. Customer Service Calls vs Churn
<img width="460" height="247" alt="image" src="https://github.com/user-attachments/assets/12f6a615-05f4-464a-ab6f-adffc18ed515" />


Donut chart showing the relationship between customer service
call volume (Total: 5.1k) and churn behavior —
highlighting how service interactions correlate with customer retention.

## Key Insights
- **Fiber optic** users have the highest churn rate at 43.96% —
  targeted retention campaigns needed
- **Month-to-month** contracts drive high revenue but pose the
  greatest churn risk
- **Average daily call minutes of 577.76** indicates high network
  usage — infrastructure planning opportunity
- **Customer service call volume** of 5.1k suggests significant
  support demand that may be driving churn

## Tools Used
| Tool | Purpose |
|------|---------|
| Apache Superset | Dashboard & visualization |
| SQL | Data querying & aggregation |
| Docker | Local deployment |
| Excel | Data preparation & cleaning |
| Python (Jupyter Notebook) | Data analysis & exploration |

## Files in This Repo
- `telecom-executive-kpi-dashboard.pdf` — Full dashboard export
- `notebooks/` — Jupyter Notebook for Python data analysis
- `screenshots/` — Individual chart screenshots

## Author
**Ndayambaje Alexis**
Data Analytics Intern — MTN Rwanda
📧 alexsaranda2@gmail.com
🔗 [GitHub Profile](https://github.com/Saranda1234)
