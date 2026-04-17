# Online Retail: Revenue, Customer Value & Risk Analysis

## 📌 Project Overview
A mid-sized UK-based online retail company had accumulated two years of transactional sales data but lacked clear visibility into customer value, product performance, and return behavior. While revenue grew, leadership was uncertain about growth sustainability and which customer segments were driving profitability

This project provides a structured, data-driven assessment to identify high-value customers, evaluate return exposure, and support targeted marketing and operational decisions.

## 🛠️ Tech Stack & Approach
The project was executed in three structured phases:

* **SQL (PostgreSQL):** Cleaned raw transactional data and developed a pipeline to evaluate revenue trends, RFM metrics, cohort retention, and churn-adjusted lifetime value.
* **Python:** Engineered behavioral features (recency, frequency, spend) and applied **K-Means Clustering** to segment customers into distinct behavioral groups.
* **Power BI:** Developed a multi-page executive dashboard highlighting revenue performance, return exposure, and a **3-month revenue forecast**.

## 📈 Key Findings
* **High Revenue Concentration:** Approximately **32% of customers** contribute nearly **84% of total gross revenue**.
* **Geographic Risk:** 96% of total revenue originates from the UK market. While the UK return rate is 3.77%, **France (33.36%) and Spain (11.28%)** exhibit exceptionally high return risks.
* **Distorted Product Metrics:** Certain products appear as top revenue drivers but have near 100% return rates, such as "Paper Craft, Little Birdie" (£168k gross revenue, 100% returns).
* **The "Leaky Bucket" Problem:** Cohort analysis reveals that only **~21% of customers** return after their first purchase, indicating substantial early churn.

## 💡 Strategic Recommendations
* **Prioritize High-Value Retention:** Focus retention initiatives on the top 32% of customers through tiered loyalty programs and proactive churn monitoring.
* **Reduce Geographic Concentration:** Evaluate expansion into stable, lower-return markets like the Netherlands (0.56% returns) and Germany (1.48% returns).
* **Operational Review:** Conduct a targeted review of logistics and quality control for the French and Spanish markets to address high return rates.
* **Adopt Return-Adjusted KPIs:** Shift inventory and marketing focus toward net profitability rather than gross sales.
* **Strengthen Early-Stage Retention:** Improve second-order conversion through post-purchase follow-ups and incentivized offers to reduce the 80% early churn rate.

---

## 📂 Repository Structure
* `data/`: Project datasets (raw and processed).
* `sql/`: PostgreSQL scripts for cleaning and business analysis.
* `python/`: Jupyter Notebook for K-Means clustering and feature engineering.
* `dashboard/`: Power BI `.pbix` file and visualization screenshots.
* `docs/`: Detailed Executive Summary PDF.

---
