# My-Excel-project
📊 Excel Retail & Sales Analysis Project
A Data Technician Bootcamp – Week 1 Project

This project showcases the Excel skills I developed during Week 1 of the Data Technician Bootcamp. The work focuses on analysing retail and sales datasets using formulas, data cleaning techniques, PivotTables, the SWITCH function, and visualisations to produce clear, meaningful insights.

📁 Project Overview
Throughout this project, I worked with multiple datasets including retail sales, student grades, bike sales, and county‑level product performance. I converted raw data into structured Excel tables, applied formulas to calculate totals and averages, built PivotTables to summarise trends, and created charts to support business insights.

This project demonstrates how Excel can be used as a BI tool to clean, analyse, and visualise data effectively.

🛠️ Skills & Techniques Used
🔢 Excel Formulas
I used a wide range of formulas to analyse and summarise data:

SUM – calculating total commission

SUMIF – conditional totals

AVERAGE – calculating mean values

AVERAGEIF – conditional averages

DATE, MONTH, YEAR – extracting date components

UNIQUE – identifying distinct values

VLOOKUP – retrieving data from lookup tables

These formulas were applied across tasks such as calculating student averages, analysing retail commissions, and summarising sales volumes.

🔍 Filtering & Sorting
Sorting customer ages from largest to smallest

Filtering datasets to focus on specific groups

Removing hidden spaces in numerical fields (e.g., Sales Volume)

Ensuring correct data types before analysis

📊 PivotTables
I created multiple PivotTables to summarise data, including:

Retail sales by age group

Bike sales by country, gender, and market segment

Product sales by county

Customer trends and profitability insights

These PivotTables helped reveal patterns such as:

Germany having customers only in adult markets

Australia showing sales across all market segments

Adults (35–64) being the strongest customer group

Gaps in France’s adult male market

🔄 SWITCH Function
Used to categorise product sales volumes:

High ( > 600 )

Medium (300–600)

Low ( < 300 )

Formula used:

Code
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")
This helped classify product performance clearly and consistently.

📈 Charts & Visualisations
I created charts from PivotTables to show:

Customer trends

Sales performance

Market gaps

Renewal‑stage customer loss (Day 4 analysis)

Charts were used to support presentations and explain insights clearly to senior leaders.

📂 Included Outputs
Retail sales table (converted using Ctrl+T)

Student grades table with averages and highest scores

Multiple PivotTables summarising sales data

SWITCH‑based categorisation column

Pivot charts from the Bike Sales Visualisation Lab

Renewal‑stage customer retention analysis

📘 Key Learning Outcomes
Strengthened confidence in Excel as a BI tool

Learned how to clean and prepare messy datasets

Improved ability to summarise data using PivotTables

Practised categorisation logic using SWITCH

Developed clear visualisations for business storytelling

Understood how Excel supports decision‑making in BI roles

📁 Project Structure
Code
📦 Excel-Retail-Sales-Project
│
├── Retail_Sales_Analysis.xlsx
├── Student_Grades_Table.xlsx
├── Bike_Sales_Pivot_Lab.xlsx
├── Bike_Sales_Visualisations.xlsx
│
└── README.md   ← You are here
