📊 Sales & Shipment Analytics Dashboard using Power BI

📌 Project Overview

This project focuses on analyzing shipment and sales operations to uncover revenue patterns, product performance, and regional trends.

The dashboard was built using Power BI, applying data modeling, DAX calculations, and interactive visuals to support faster and smarter business decisions.

🎯 Objectives

Monitor overall sales and shipment KPIs

Compare current results vs last year

Identify top-performing products

Analyze geo contribution

Track salesperson effectiveness

Understand shipment volume distribution

🗂 Dataset Architecture

The model follows a fact & dimension approach similar to enterprise BI systems.

🚚 Shipments (Fact)

ShipmentID

SPID

PID

GID

Shipdate

Amount

Boxes

Order_Status

📦 Products

Product

Category

Cost_per_box

PID

🌍 Geography

Geo

Region

GID

👨‍💼 Salesperson

Sales_person

Team

Picture

SPID

📅 Calendar

cal_date

Month_num

month_name

year

weekday_num

weekday_name

🧹 Data Preparation & Transformation

Performed using Power Query.

Validated foreign keys

Standardized data types

Enabled time intelligence

Structured tables for analytical performance

🧠 Feature Engineering (Columns Added)

To enhance reporting:

Start of Month → monthly grouping

First Name → cleaner display in leaderboard

Cost → boxes × cost per box

Boxes (bins) → shipment size segmentation

📐 DAX Measures & Calculations

Core metrics built for analytics:

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

📊 Executive KPIs

The dashboard highlights:

✅ Total Amount
✅ Total Boxes
✅ Shipment Count
✅ Total Profit
✅ Profit Pct

📈 Visual Analytics
📅 Trend Comparison

Line charts help compare:

Current performance

Last year

Variance across months

Quickly reveals growth or decline.

🌍 Regional Revenue View

Donut chart representing contribution by geography.

📦 Shipment Pattern

Clustered columns using bins to show how frequently each shipment size occurs.

👨‍💼 Sales Leaderboard

Dynamic ranking with:

Image

First Name

Total Amount

Total Boxes

Revenue %

Changes based on slicer selections.

🏆 Product Contribution

Ranked table

Treemap for top performers

🔍 Insights Generated

Easy visibility into YoY changes

Revenue dependency on certain products

Clear regional demand patterns

Sales performance shifts based on filters

Majority shipments belong to specific size ranges

🛠 Technology Stack

Power BI Desktop

Power Query

DAX

Excel

💼 Business Impact

This solution enables:

✔ Faster decision-making
✔ Consistent KPI measurement
✔ Identification of revenue drivers
✔ Better target & incentive planning
✔ Reduced manual reporting effort

📂 Repository Includes

Power BI report (.pbix)

Source dataset

Dashboard screenshots

👨‍💻 Author

Thirupal
Junior Data Analyst
Power BI | SQL | Python | Excel
