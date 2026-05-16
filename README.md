# 🚀 E-Commerce Online Retail Data Analytics Project

This repository contains an end-to-end data analytics and business intelligence project focused on an Online Retail dataset from the UCI Machine Learning Repository. The project covers data exploration, rigorous data cleaning, descriptive sales analysis, actionable business insight generation, and advanced customer metrics calculations including Customer Lifetime Value (CLV).

Dataset Link: [UCI Machine Learning Repository - Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)

---

## 📌 Project Overview
This project aims to analyze transactional data from a UK-based online retail store to understand sales performance, geographical distribution, customer purchase behavior, and long-term customer value. The analysis serves as a comprehensive tool to drive data-backed decision-making for marketing, inventory management, and customer retention strategies.

---

## 🛠️ Project Architecture & Workflow

### Data Exploration
* Initial assessment of the dataset to understand the layout, structure, and attributes of the data.
* Checking data types, identifying missing observations, and validating dataset dimensions across all columns before performing any modifications.

### Data Cleaning
* Handling missing values systematically to prevent bias in subsequent statistical summaries.
* Detecting and removing duplicate transactional records to maintain data integrity.
* Filtering out anomalous data points such as negative quantities or pricing errors representing cancellations or data entry faults to ensure clean downstream analysis.

### Sales Analysis
* Calculation of the KPI Summary to evaluate overall revenue performance and total transactional volume.
* Deep-dive visual exploration of sales distribution across various dimensions to uncover high-performing markets and items.

### Business Insight Determination
* Translating raw visual patterns and data aggregates into strategic corporate recommendations.
* Aligning statistical findings with operational improvements in stock allocation, marketing timelines, and geographic positioning.

### Customer Lifetime Value Calculation
* Applying data science methodology to calculate and map out the long-term monetary worth of each customer.
* Identifying the highest-value individual accounts to enable precision targeted marketing and loyalty program optimizations.

---

## 📊 Key Findings & Visualizations

* **Top 10 Country Sales:** The analysis reveals that the United Kingdom commands an overwhelming majority of the store's total revenue, followed by key European markets including the Netherlands and EIRE.
* **Monthly Sales Trend:** A major macroeconomic peak occurred in November 2011, exhibiting a sharp upward surge in sales driven by seasonal shopping behavior or year-end promotional activities before dropping off in December.
* **Top 10 Product by Sales:** Product code '22423' (REGENCY CAKESTAND 3 TIER) ranks as the single largest revenue-generating item, strongly dominating the remaining inventory in total sales value.
* **Heatmap Sales by Day and Hour:** Customer transaction habits show extreme concentration on weekdays (Monday through Thursday) precisely during the midday window of 10:00 to 15:00. Notably, Saturdays recorded zero sales transactions.
* **Top 10 Customer Lifetime Value:** Advanced metrics successfully identified specific top-tier accounts, notably Customer ID 14646 and 18102, as the most highly profitable assets to target for exclusive loyalty retention.

---

## 💡 Strategic Business Recommendations

1. **Inventory & Supply Optimization:** Prioritize stock safety levels and continuous supply chains for high-demand items like the Regency Cakestand to capitalize on consistent demand.
2. **Precision Marketing Schedules:** Align digital promotions, newsletter distributions, and ad campaign launches with peak shopping hours between 10:00 and 15:00 from Monday to Thursday to maximize conversion rates.
3. **Geographic Expansion:** Design localized retention marketing and tailored promotional packages for secondary high-value international markets like the Netherlands and EIRE to diversify revenue away from complete UK dependence.
4. **VIP Loyalty Strategy:** Develop high-touch customer management workflows specifically for top CLV identifiers (such as Customer ID 14646) to secure recurring high-margin purchase orders.

---

## 💻 Tech Stack & Requirements
* Python 3.x
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Openpyxl (for Excel-based data loading)

---

## 🏃 How to Run the Project
1. Clone this repository to your local workstation:
   ```bash
   git clone [https://github.com/yourusername/online-retail-analysis.git](https://github.com/yourusername/online-retail-analysis.git)
