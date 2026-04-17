# Online Retail: Revenue, Customer Value & Risk Analysis

## 📌 Project Overview
[cite_start]A mid-sized UK-based online retail company had accumulated two years of transactional sales data but lacked clear visibility into customer value, product performance, and return behavior[cite: 3]. [cite_start]While revenue grew, leadership was uncertain about growth sustainability and which customer segments were driving profitability[cite: 4].

[cite_start]This project provides a structured, data-driven assessment to identify high-value customers, evaluate return exposure, and support targeted marketing and operational decisions[cite: 5].

## 🛠️ Tech Stack & Approach
[cite_start]The project was executed in three structured phases[cite: 12]:

* [cite_start]**SQL (PostgreSQL):** Cleaned raw transactional data and developed a pipeline to evaluate revenue trends, RFM metrics, cohort retention, and churn-adjusted lifetime value[cite: 14, 15].
* [cite_start]**Python:** Engineered behavioral features (recency, frequency, spend) and applied **K-Means Clustering** to segment customers into distinct behavioral groups[cite: 17, 18].
* [cite_start]**Power BI:** Developed a multi-page executive dashboard highlighting revenue performance, return exposure, and a **3-month revenue forecast**[cite: 21].

## 📈 Key Findings
* [cite_start]**High Revenue Concentration:** Approximately **32% of customers** contribute nearly **84% of total gross revenue**.
* [cite_start]**Geographic Risk:** 96% of total revenue originates from the UK market[cite: 27]. [cite_start]While the UK return rate is 3.77%, **France (33.36%) and Spain (11.28%)** exhibit exceptionally high return risks[cite: 31, 32, 36].
* [cite_start]**Distorted Product Metrics:** Certain products appear as top revenue drivers but have near 100% return rates, such as "Paper Craft, Little Birdie" (£168k gross revenue, 100% returns)[cite: 41, 44].
* [cite_start]**The "Leaky Bucket" Problem:** Cohort analysis reveals that only **~21% of customers** return after their first purchase, indicating substantial early churn[cite: 50].

## 💡 Strategic Recommendations
* [cite_start]**Prioritize High-Value Retention:** Focus retention initiatives on the top 32% of customers through tiered loyalty programs and proactive churn monitoring[cite: 54, 57, 60].
* [cite_start]**Reduce Geographic Concentration:** Evaluate expansion into stable, lower-return markets like the Netherlands (0.56% returns) and Germany (1.48% returns)[cite: 34, 35, 63].
* [cite_start]**Operational Review:** Conduct a targeted review of logistics and quality control for the French and Spanish markets to address high return rates[cite: 65, 67].
* [cite_start]**Adopt Return-Adjusted KPIs:** Shift inventory and marketing focus toward net profitability rather than gross sales[cite: 74, 75].
* [cite_start]**Strengthen Early-Stage Retention:** Improve second-order conversion through post-purchase follow-ups and incentivized offers to reduce the 80% early churn rate[cite: 78, 80, 81].

---

## 📂 Repository Structure
* `data/`: Project datasets (raw and processed).
* `sql/`: PostgreSQL scripts for cleaning and business analysis.
* `python/`: Jupyter Notebook for K-Means clustering and feature engineering.
* `dashboard/`: Power BI `.pbix` file and visualization screenshots.
* `docs/`: Detailed Executive Summary PDF.

---