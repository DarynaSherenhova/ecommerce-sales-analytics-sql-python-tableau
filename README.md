# ecommerce-sales-analytics-sql-python-tableau
This end-to-end analytics project demonstrates data analysis and visualization for an online store using **SQL**, **Python**, and **Tableau**.

## Goal

To showcase skills in:

- Extracting data from a Google BigQuery database using SQL
- Performing exploratory and statistical analysis using Python
- Building an interactive dashboard using Tableau Public

---

## Tools & Technologies

- Google BigQuery (SQL)
- Python (Pandas, Matplotlib, Seaborn, Scipy)
- Tableau Public

---

## 🗂Dataset Overview

Extracted from a simulated e-commerce platform via SQL from Google BigQuery.  
It includes:

- Order and session metadata
- User details (device, registration, email confirmation, newsletter status)
- Product attributes (category, name, price)
- Traffic source info (channel, browser, language)

The dataset contains:

- ✅ Numerical columns: `price`, etc.
- ✅ Categorical columns: `country`, `device`, `traffic_channel`, etc.
- ✅ Date columns: `order_date`, `session_id`
- ✅ Unique sessions: ~N
- ✅ Date range: YYYY-MM-DD to YYYY-MM-DD
- ✅ Missing values: present in user metadata fields

---

## Key Business Questions Answered

- Which continents and countries drive the most sales?
- What are the top-selling product categories globally and regionally?
- How do device types and models impact sales?
- What traffic sources generate the most revenue?
- Do registered or subscribed users behave differently?
- Is there a correlation between sessions and sales?
- 🗓Do sales show temporal patterns or seasonal trends?

---

## Analysis Performed

- Exploratory Data Analysis
- Statistical significance testing (t-tests, correlation coefficients)
- Pivot tables & grouped aggregations
- Data visualization (bar charts, time series, heatmaps)

---

## Tableau Dashboard

A 2-page Tableau dashboard was created and published on Tableau Public, including:

- Dynamic filters by region, category, and device
- KPI tracking (sales, sessions, registration rate)
- Sales trend visualizations across time, regions, and channels

👉 [Click to View Dashboard on Tableau Public](https://public.tableau.com/app/profile/daryna.sherenhova8856/viz/Salesanalysis_17484619552220/SalesAnalysis)

---


