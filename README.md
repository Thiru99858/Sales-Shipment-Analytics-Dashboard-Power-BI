📊 Sales & Shipment Analytics Dashboard – Power BI

📌 Project Overview

This project presents an interactive Sales & Shipment Analytics Dashboard developed using Power BI.
It transforms raw shipment data into meaningful insights that help monitor revenue, volume, profitability, regional demand, and salesperson performance.

🎯 Business Objective

Provide a quick executive KPI view

Compare current results with previous year

Identify top revenue-generating products

Understand geo contribution

Track individual salesperson effectiveness

📦 Data Model
Fact Table – Shipments

ShipmentID

SPID

PID

GID

Shipdate

Amount

Boxes

Order_Status

Dimension Tables

Products

Product

Category

Cost_per_box

PID

Geography

Geo

Region

GID

Salesperson

Sales_person

Team

Picture

SPID

Calendar

cal_date

Month_num

month_name

year

weekday_num

weekday_name

🧹 Data Preparation

Verified keys between fact & dimension tables

Adjusted data types

Prepared date structure for time analysis

Organized reporting model

🧠 Additional Columns Created

Start of Month for trend reporting

First Name for easy identification

Cost calculated from boxes and cost per box

Boxes (bins) for shipment distribution analysis

📐 DAX Measures

Total Amount

Total Boxes

Shipment Count

Total Cost

Total Profit

Profit Pct

Amount Per Box

Total Amount (Last Year)

Total Amount (12 Months Variance)

Total Boxes (Last Year)

Total Boxes (12 Months Variance)

Total % contribution

📊 KPIs Displayed

Total Amount

Total Boxes

Shipment Count

Total Profit

Profit Pct

📈 Report Highlights
Year vs Last 12 Months

Line charts comparing sales and volume trends to quickly identify increases or drops.

Geo Analysis

Donut chart visualizing how each region contributes to total revenue.

Shipment Size Distribution

Clustered column chart to understand frequency of small vs large orders.

Salesperson Leaderboard

Interactive ranking with:

Photo

First Name

Total Amount

Total Boxes

Contribution %

Product Performance

Revenue table

Treemap of top products

🔍 Insights Enabled

Easy comparison of present vs past performance

Visibility of revenue concentration among key products

Clear view of regional strengths

Performance evaluation of sales team

Understanding shipment behavior patterns

🛠 Tools Used

Power BI Desktop

Power Query

DAX

Excel

💼 Business Benefits

Faster management reporting

Better planning & forecasting

Consistent KPI definitions

Reduced manual analysis effort

📂 Files Included

.pbix report

Excel dataset

Dashboard screenshots

👨‍💻 Author

Thirupal
Junior Data Analyst
Power BI | SQL | Python | Excel
