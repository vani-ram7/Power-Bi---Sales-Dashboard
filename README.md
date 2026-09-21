☕ Cafe Sales Dashboard

An interactive Power BI dashboard designed to analyze cafe sales
performance using transaction-level sales data. The report combines
sales metrics, product information, payment methods, locations, and a
dedicated date table to provide an easy-to-understand view of business
performance.

📊 Project Overview

The Cafe Sales Dashboard helps transform raw cafe transaction data
into meaningful business insights. It provides interactive
visualizations and KPI cards for monitoring sales, quantity, pricing,
and time-based performance.

The dashboard is built in Microsoft Power BI and uses a structured
DateTable for year, quarter, month, and day analysis.

🎯 Objectives

Monitor overall cafe sales performance.

Analyze sales across different products/items.

Compare performance by location.

Understand customer payment-method usage.

Track quantity and pricing information.

Analyze monthly, quarterly, and yearly trends.

Provide interactive filtering for business analysis.

🛠️ Tools & Technologies

Microsoft Power BI

Power Query -- data preparation and transformation

DAX -- calculated measures and time-based analysis

Data Modeling -- relationships between sales and date data

Interactive Visualizations -- charts, cards, slicers, and tables

🗂️ Data Model

The report contains the following main components:

dirty_cafe_sales

The primary transaction-level sales table containing fields such as:

Transaction ID

Item

Quantity

Price Per Unit

Payment Method

Location

Date-related fields

DateTable

A dedicated date dimension used for time intelligence and filtering. It
includes:

Date

Year

Quarter

Month

Day

Year Hierarchy

Measure Table

A dedicated table containing report measures, including:

Total_Sales

pre_sales

Sales_QTD

Sales YTD

Month MTD

📈 Dashboard Features

The report includes interactive Power BI visuals such as:

Total Sales KPI

Sales trend and comparison visuals

Item/Product analysis

Location analysis

Payment Method analysis

Quantity analysis

Price-related analysis

Year / Quarter / Month slicers

Interactive tables

Time-intelligence metrics

⏱️ Time Intelligence

The DateTable enables analysis at multiple time levels:

Year
 └── Quarter
      └── Month
           └── Day

The report includes measures for:

MTD -- Month-to-Date

QTD -- Quarter-to-Date

YTD -- Year-to-Date

This makes it possible to compare sales performance across different
periods.

🔍 Key Business Questions

The dashboard can be used to answer questions such as:

What is the total sales generated?

Which items contribute most to sales?

How does sales performance vary by location?

Which payment methods are used most frequently?

How many units are being sold?

How does sales performance change by month, quarter, and year?

What is the current MTD, QTD, and YTD performance?

📁 Project Structure

Cafe-Sales-Dashboard/
│
├── DateTable.pbix
└── README.md

🚀 How to Use

Download or clone this repository.

Open DateTable.pbix using Microsoft Power BI Desktop.

Navigate through the dashboard pages.

Use the slicers to filter the report by available time periods and
categories.

Interact with the charts and tables to explore sales performance.

💡 Skills Demonstrated

This project demonstrates practical skills in:

Power BI Dashboard Development

Data Visualization

Data Cleaning & Transformation

Data Modeling

DAX Measures

Time Intelligence

KPI Development

Interactive Reporting

Business Data Analysis

📌 Project Highlights

Cafe Sales Dashboard converts transaction data into an interactive
business intelligence report, making it easier to understand sales
patterns, product performance, locations, payment behavior, and
time-based trends.

👤 Author

Vani

GitHub: https://github.com/vani-ram7

⭐ If you find this project useful, consider giving the repository a
star.
