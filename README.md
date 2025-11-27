📊 Finance KPI Dashboard – Power BI
📌 Project Overview

This project showcases a comprehensive Finance KPI Dashboard built using Power BI. It tracks monthly performance by comparing Actual Sales vs. Target Sales, highlights variance, and provides clear insights into team and individual salesperson performance.
The dashboard is fully dynamic, interactive, and designed for quick financial decision-making.

🚀 Key Features:

1. Data Preparation & Cleaning

Used Power Query to clean and transform multiple data tables.
Converted matrix-style data into a proper tabular format using Unpivot.
Ensured standardized date formats and consistent data types.

2. Data Modeling

Built a star-schema model including:
FactActuals (Actual Sales)
FactTargets (Target Sales)
DimCalendar
DimPeople

Created relationships between fact tables and dimensions for accurate analysis.

3. DAX Measures

Implemented essential financial KPIs:
Total Sales (Actual)
Total Sales (Target)
Variance (Actual – Target)
Variance %
Year-to-Date (YTD) Actuals & Targets
YTD Variance and %
Count of Months Where Target Was Achieved
Dynamic Titles & Labels that change based on slicer selections

4. Interactive Visualizations

The dashboard includes:

KPI Cards showing Actual, Target, and Variance (with YTD indicators)
Win/Loss Chart to highlight months where targets were met or missed
Actual vs. Target Column Chart with variance percentage labels
Team Performance Table:
Actual vs Target
Variance (with colored data bars)
Mini sparklines showing each salesperson’s monthly trend
Profile Images loaded using image URLs for each salesperson
Emoji Indicators for positive/negative performance

5. Dynamic User Experience

Slicers to filter by Salesperson or Team
All visuals automatically update according to the selection
Dynamic titles update to match the filtered salesperson or group
Smart Narrative visual included for automatic text-based insights

🛠 Technologies Used

Power BI Desktop
Power Query
DAX (Data Analysis Expressions)

🙏 Credits

This dashboard was inspired by and built while following the YouTube tutorial:

🎥 YouTube Video: https://youtu.be/i3AR0gt9SHA
👤 Creator: Chandoo
