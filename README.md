📊 COVID-19 Analysis Dashboard (Power BI)

A comprehensive COVID-19 data analytics dashboard built using Power BI to analyze global confirmed cases, deaths, recoveries, mortality ratios, and regional trends.

This project showcases data cleaning, modeling, visualization, and insights generation using advanced Power BI features.

🚀 Project Overview

This Power BI project provides an interactive and visually compelling analysis of worldwide COVID-19 impact using dashboards that highlight:

Global confirmed cases

Global deaths & death rate

Weekly growth rate

Country-wise comparison

WHO regional distribution

Recovery vs death vs active cases

Mortality ratio insights

Geographic distribution of deaths

The dashboard is built to help understand the spread, severity, and recovery performance across countries and regions.

📂 Dashboard Pages
1️⃣ COVID-19 Confirmed & Death Cases Overview

✔ Top 10 countries with the highest confirmed cases
✔ WHO region-wise distribution (Donut chart)
✔ Worldwide deaths map
✔ Top 10 countries with highest deaths
✔ Key KPIs:

Total Confirmed

Weekly Growth %

Total Deaths

Death Rate %

📸 Dashboard Preview:


Replace with your uploaded image URL after pushing images to GitHub.

2️⃣ COVID-19 Death vs Recovered vs Active

✔ Recovery vs Death vs Active proportions
✔ Country-wise comparison using stacked bars
✔ Mortality Ratio vs Recovery Ratio scatter plot
✔ Top 10 countries death-analysis
✔ KPIs:

Total Recoveries

Total Active Cases

Recovery Ratio

Mortality Ratio

📸 Dashboard Preview:


🧹 Data Cleaning & Transformation

Performed in Power Query:

Removed duplicates

Handled missing/null values

Converted data types

Standardized country/region names

Created calculated columns for mortality & recovery ratios

Merged WHO region data

🧮 Important DAX Measures Used
Total Confirmed = SUM(Data[Confirmed])
Total Deaths = SUM(Data[Deaths])
Total Recovered = SUM(Data[Recovered])
Total Active = [Total Confirmed] - ([Total Deaths] + [Total Recovered])

Death Rate % = ([Total Deaths] / [Total Confirmed]) * 100
Recovery Rate % = ([Total Recovered] / [Total Confirmed]) * 100
Weekly Growth % = ( ([This Week] - [Last Week]) / [Last Week] ) * 100
Mortality Ratio = ([Total Deaths] / [Total Recovered]) * 100


(More DAX can be added based on your file—tell me if you want them listed.)

🗺️ Key Insights
🔹 Global Overview

16.48M+ confirmed cases

0.65M+ total deaths

Global death rate: ~3.9%

12% weekly growth rate

🔹 Country Analysis

The US leads with the highest confirmed cases & deaths

Brazil and India follow

European region shows a high share of confirmed cases

🔹 Recovery & Mortality

Global recovery ratio ~58%

Countries like Chile, Iran, Mexico show higher mortality ratios

Countries like India, Brazil show stronger recovery performance


🛠️ Tools & Technologies

Power BI Desktop

Power Query (ETL)

DAX (Advanced Calculations)

Bing Maps Visual

Donut/Bar/Scatter Charts

Data Modeling

🎯 Purpose of the Project

This project demonstrates:

Analytical storytelling

Dashboard design principles

KPI building and interpretation

Advanced Power BI features

Real-world dataset analysis

End-to-end data analysis workflow

This repository is ideal for recruiters to evaluate Power BI proficiency, DAX skills, data modeling, and dashboard design ability.

📞 Contact

If you want to connect or have questions:

Your Name
📧 vishnunairofficial2004@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/vishnu-nair-b6a764341/
