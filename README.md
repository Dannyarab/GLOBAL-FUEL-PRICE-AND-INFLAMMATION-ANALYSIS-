# 🌍 Global Fuel Price & Inflation Analysis Dashboard

"Power BI" (https://img.shields.io/badge/Tool-Power%20BI-yellow?style=for-the-badge&logo=powerbi)
"Data Analysis" (https://img.shields.io/badge/Field-Data%20Analysis-blue?style=for-the-badge)
"Status" (https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)
"License" (https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)
"Made With" (https://img.shields.io/badge/Made%20With-DAX-orange?style=for-the-badge)

---

📌 Project Overview

This project presents an interactive Power BI dashboard that analyzes global fuel prices and their relationship with inflation across multiple countries. The goal is to provide clear insights into how fuel price variations impact economic conditions over time.

---

🎯 Objectives

- Analyze fuel price differences across countries
- Examine inflation trends over time
- Explore the relationship between fuel prices and inflation
- Build an interactive dashboard for easy data exploration

---

📂 Datasets Used

1. all_countries_combined.csv
   
   - Country-level economic indicators over time
   - Includes Year, CPI, Inflation Deflator (2024 adjusted)

2. manifest.csv
   
   - Fuel price data by country
   - Includes price per liter (USD)

---

🧹 Data Cleaning & Preparation

- Removed duplicates
- Handled missing values (median for numeric, mode for categorical)
- Standardized column names
- Converted year to proper format
- Created a Country Lookup Table for proper relationships

---

🔗 Data Modeling

Used a star schema model:

- Country_Lookup (Dimension Table)
- Fact Tables:
  - all_countries_cleaned
  - manifest_cleaned

Relationships:

- Country_Lookup → all_countries_cleaned
- Country_Lookup → manifest_cleaned

---

📊 Key Metrics (DAX)

- Average Fuel Price
- Max Fuel Price
- Min Fuel Price
- Inflation Rate (%) (derived from CPI)

---

📈 Dashboard Features

🔹 KPI Cards

- Avg Fuel Price
- Inflation Rate (%)
- Highest Fuel Price
- Lowest Fuel Price

🔹 Visuals

- Bar Chart → Fuel Price by Country
- Line Chart → Inflation Trend Over Time
- Scatter Plot → Fuel Price vs Inflation

🔹 Interactivity

- Country slicer (dropdown with search)
- Dynamic filtering across visuals

---

🔍 Key Insights

- Higher fuel prices are generally associated with higher inflation
- Fuel prices vary significantly across countries
- Inflation trends fluctuate over time
- Fuel cost is a key economic driver

---

🧠 Skills Demonstrated

- Data Cleaning
- Data Modeling (Star Schema)
- DAX Calculations
- Data Visualization
- Insight Communication

---

🚀 Tools Used

- Power BI
- DAX
- CSV Data Sources

---

📌 How to Use

1. Use the country slicer to filter
2. Compare fuel prices via bar chart
3. Analyze inflation trends via line chart
4. Explore relationships using scatter plot

---

📎 Conclusion

This dashboard provides a clear, interactive view of how fuel prices influence inflation globally, enabling better understanding of economic patterns.

---

👤 Author

Daniel Alhassan
Data Analyst
