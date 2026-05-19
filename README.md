# 📊 Data Professional Survey Breakdown (Power BI)

## 📌 Project Overview
This project presents a comprehensive, data-driven breakdown of the global data professional community. Based on a real-world survey of over 630 data professionals (Data Scientists, Data Engineers, Data Analysts, etc.), this interactive Power BI dashboard provides key insights into global tech stacks, industry salary benchmarks, work-life balance, and overall job satisfaction.

The core challenge of this project was data cleansing and transformation of highly unstructured survey responses into a structured star schema model.

## 🛠 Key Features & Data Cleansing Steps
Using Power Query, the raw, messy survey data underwent several rigorous transformation steps:
* **Data Cleansing:** Split, unpivoted, and cleaned messy text columns (e.g., standardizing custom-entered country names and programming languages).
* **Demographic Segmentation:** Visualized geographic concentration of data professionals, highlighting major hubs like the United States, India, and the United Kingdom.
* **KPI Metrics:** Computed precise gauges and cards to track qualitative metrics such as *Average Satisfaction with Work-Life Balance* and *Average Satisfaction with Salary*.

## 📊 Dashboard Visuals
Here is the final interactive interface built within Power BI:
<img width="1133" height="624" alt="Final_project_BI" src="https://github.com/user-attachments/assets/add20549-152e-4807-ba91-a333e716e5a8" />


## 💡 Key Analytical Insights
1. **The Tech Stack King:** Python overwhelmingly dominates as the favorite programming language among data professionals globally, leaving R and other alternatives significantly behind.
2. **The Career Progression:** Data Scientists and Data Engineers hold the highest average salary benchmarks, while Data Analysts and Database Developers represent a steady mid-tier bracket.
3. **The Satisfaction Gap:** While work-life balance satisfaction scores remain moderately high (5.86 out of 10), general salary satisfaction lags slightly behind at 4.27, providing an interesting look into industry standards and employee expectations.

## 🧰 Tools Used
* **Power BI Desktop:** Dashboard development, themes, and interactive Gauge/Treemap visualizations.
* **Power Query:** Advanced data cleaning, column splitting, conditional logic, and text standardization.
* **Microsoft Excel:** Raw survey dataset source.
