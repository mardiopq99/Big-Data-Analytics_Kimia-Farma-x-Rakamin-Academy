# Kimia Farma Performance Analytics Dashboard

## Overview
**Kimia Farma** is one of Indonesia's largest pharmaceutical companies, operating across various regions. This project analyzes Kimia Farma's business performance from **2020 to 2023** using **BigQuery** for data aggregation and **Looker Studio** for dashboard visualization.

## Project Workflow
1. **Data Aggregation:**
   - Extracted transactional, branch, and product data from **BigQuery**.
   - Processed key financial metrics such as **Nett Sales** and **Nett Profit**.
   - Defined business insights using SQL queries.

2. **Data Visualization:**
   - Connected the aggregated data to **Looker Studio**.
   - Created interactive dashboards with filters, charts, and geo-maps.
   
## Key Dashboard Insights
- **Revenue Comparison (2020-2023):** Revenue fluctuated, with 2023 showing the highest growth.
- **Top 10 Branches by Total Transactions:** Major transactions occurred in **Jakarta, Surabaya, and Bandung**.
- **Top 10 Branches by Nett Sales:** Highest nett sales were recorded in **Jakarta and Surabaya**.
- **Top 5 Branches with High Ratings but Low Transactions:** Indicates potential marketing or operational inefficiencies.
- **Profit Distribution (Geo Map):** Certain provinces showed higher profitability, highlighting market potential.

## Business Recommendations
| Strategy | Details |
|----------|---------|
| **Optimize High-Rated Branches** | Enhance visibility of branches with high ratings but low transactions through targeted promotions. |
| **Strengthen High-Profit Regions** | Increase inventory and marketing efforts in provinces with high nett profit. |
| **Yearly Sales Trend Analysis** | Implement dynamic pricing and seasonal promotions based on yearly sales patterns. |
| **Branch-Level Performance Review** | Identify and address operational inefficiencies in branches with declining performance. |

## Technologies Used
- **BigQuery** (Data Processing & Aggregation)
- **Google Looker Studio** (Dashboard Visualization)
- **SQL** (Data Transformation)
- **Google Cloud Platform** (Storage & Query Processing)

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/kimia-farma-dashboard.git
   ```
2. Connect to BigQuery and Looker Studio.
3. Open the Looker Studio dashboard to explore insights interactively.

## Author
Created by **Mardio Edana Putra** as part of the Big Data Analytics project for Kimia Farma.

## License
This project is licensed under the **MIT License**.
