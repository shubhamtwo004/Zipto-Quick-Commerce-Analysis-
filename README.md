# 📊 Zipto Dark Store Performance Analysis

## 📌 Project Overview

Zipto Dark Store Performance Analysis is a data analytics project focused on identifying underperforming stores, evaluating delivery operations, and analyzing product profitability and promotional discounts.

The project uses Excel, MySQL, and an interactive dashboard to transform raw data into meaningful business insights and identify potential opportunities for operational and financial improvement.

## 🎯 Business Objectives

- Analyze store-level performance and profitability.
- Evaluate delivery time, delivery costs, and return rates.
- Analyze product category margins and promotional performance.
- Identify potential promotional discount leakage.
- Recommend data-driven operational improvements.

## 📂 Dataset Overview

The analysis covers **42 days of data**, from May 18 to June 28, 2026.

| Metric | Value |
|---|---:|
| Stores | 10 |
| Total Orders | 52,133 |
| Delivered Orders | 48,510 |
| Returned Orders | 2,556 |
| Cancelled Orders | 1,067 |

## 🛠️ Tools & Technologies

- **Excel / Power Query:** Data cleaning and preprocessing
- **MySQL:** Data analysis using joins, CTEs, aggregations, and validation queries
- **HTML, CSS & JavaScript:** Interactive dashboard
- **GitHub:** Project version control and hosting

## 🔍 Key Insights

- **S07:** Recorded an adjusted monthly profit of approximately **−₹372.8K**.
- **S03:** Recorded an adjusted monthly profit of approximately **−₹139.0K**.
- **Delivery scan anomaly:** Same-timestamp pickup and delivery records accounted for 19.03% of S07 trips and 16.77% of S03 trips.
- **Return rate:** Orders with the same pickup and delivery timestamp had a 34.19% return rate, compared with 3.73% for other orders.
- **Promotion compliance:** Approximately 42% of promotional orders at S03 and S07 were below the applicable minimum-order value.
- **Potential financial exposure:** Promotional discount leakage was estimated at approximately ₹174.5K per month across S03 and S07.

*Note: These findings indicate associations and potential improvement opportunities, not proven causes or guaranteed savings.*

## 💡 Recommendations

1. Investigate the same-timestamp delivery records and validate delivery scan processes.
2. Review return patterns and strengthen order fulfilment checks.
3. Enforce minimum-order requirements for promotional discounts.
4. Review promotion performance and contribution margins.
5. Monitor store profitability, delivery costs, and returns regularly.

## 📈 Project Workflow

1. Data collection and understanding
2. Data cleaning and preprocessing in Excel / Power Query
3. Data analysis and validation using MySQL
4. Store performance comparison adjusted for operating days
5. Delivery, product, and promotion analysis
6. Identification of business insights and recommendations
7. Presentation of findings through an interactive dashboard

## 🌐 Project Links

- **Live Dashboard:** [Open Dashboard](https://zipto-dark-store-analysis-kmr3joufedsiofqjfwiaea.streamlit.app/)

## ⚠️ Limitations

- The analysis covers only 42 days of data.
- Some order-item records have missing unit-cost values.
- Observed relationships do not establish causation.
- Estimated promotional leakage represents potential exposure, not guaranteed savings.


*This project demonstrates the use of data cleaning, SQL analysis, business metrics, and visualization to investigate operational performance and identify potential improvement opportunities.*# Zipto-Quick-Commerce-Analysis-
