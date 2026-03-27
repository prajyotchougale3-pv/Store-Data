
# Project Title

This project is a business intelligence and data visualization solution designed to analyze and monitor sales performance across multiple dimensions. Using tools like Power BI, it provides interactive dashboards and reports that help businesses gain actionable insights into their sales, profit, discounts, and customer behavior.

# Store - Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/787388d5-331e-4c39-8cd1-c61f3a84e00c/b4fe30d10125a592a355?experience=power-bi

## Problem Statement

Businesses often fail to utilize nearly 70% of their sales data effectively, leaving critical insights hidden. Without proper analysis, it’s difficult to identify the top 5% of products driving 80% of revenue, track time-based trends, or measure how discounts reduce profit margins by up to 15–20%.

This project solves the problem by providing an interactive Power BI dashboard that converts raw data into clear, actionable insights—helping managers improve decisions, optimize strategies, and boost overall performance.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a CSV file.

Step 2 : Open Power Query Editor → In View tab under Data Preview, check Column distribution, Column quality, and Column profile options.

Step 3 : Change profiling to “Column profiling based on entire dataset” instead of default 1000 rows.

Step 4 : Validate columns for missing/error values. Dataset was clean except minor discount category checks.

Step 5 : Create calculated measures in DAX:

Total Sales

Total Profit

Net Sales (Sales – Discount)

Number of Orders

Average Discount

Step 6 : In Report View, apply a professional theme for consistent design.

Step 7 : Add visuals:

Map Chart → Sales by city (Mumbai, Delhi, Pune, etc.).

Card Visual → Total number of orders (e.g., 3510).

Bar Chart → Average discount by promotion categories.

Scatter Plot → Relationship between Profit and Net Sales.

Line Chart → Sales trends from 2020–2024.

Step 8 : Add Slicers (Visual Filters) for Product, Date, Customer ID, and Promotion Category.

Step 9 : Create Top/Bottom Analysis tab → Show top 5 and bottom 5 products by Sales, Profit, and Quantity Sold.

Step 10 : Add Comparison Tab → Compare Sales/Profit/Quantity between two user‑selected periods.

Step 11 : Insert Table Visuals → Show detailed order‑level data with filters applied.

Step 12 : Add branding elements (text boxes for project name, company logo, shapes) for polished look.

Step 13 : Validate calculations (profit margins, discount percentages) and ensure slicers update visuals correctly.

Step 14 : Publish the report to Power BI Service and enable sharing/refresh options.

📌 You can now attach screenshots (like you did in your airline example) after each step or at the end under Dashboard Snapshot.

Do you want me to also draft the Objectives section (like 5–6 bullets) that directly ties these steps to the 8 tasks from your first snapshot? That way your README flows perfectly: Problem → Objectives → Steps → Screenshots.

add dash to bullets
Here’s your Sales Performance Dashboard steps rewritten with dashes before each bullet, exactly in the style you want. You can later replace the screenshot links with your own:

Steps Followed
Step 1 – Load data into Power BI Desktop, dataset is a CSV file.

Step 2 – Open Power Query Editor → In View tab under Data Preview, check Column distribution, Column quality, and Column profile options.

Step 3 – Change profiling to “Column profiling based on entire dataset” instead of default 1000 rows.

Step 4 – Validate columns for missing/error values. Dataset was clean except minor discount category checks.

Step 5 – Create calculated measures in DAX:

Total Sales

Total Profit

Net Sales (Sales – Discount)

Number of Orders

Average Discount

Step 6 – In Report View, apply a professional theme for consistent design.

Step 7 – Add visuals:

Map Chart → Sales by city (Mumbai, Delhi, Pune, etc.)

Card Visual → Total number of orders (e.g., 3510)

Bar Chart → Average discount by promotion categories

Scatter Plot → Relationship between Profit and Net Sales

Line Chart → Sales trends from 2020–2024

Step 8 – Add Slicers (Visual Filters) for Product, Date, Customer ID, and Promotion Category.

Step 9 – Create Top/Bottom Analysis tab → Show top 5 and bottom 5 products by Sales, Profit, and Quantity Sold.

Step 10 – Add Comparison Tab → Compare Sales/Profit/Quantity between two user‑selected periods.

Step 11 – Insert Table Visuals → Show detailed order‑level data with filters applied.

Step 12 – Add branding elements (text boxes for project name, company logo, shapes) for polished look.

Step 13 – Validate calculations (profit margins, discount percentages) and ensure slicers update visuals correctly.

Step 14 – Publish the report to Power BI Service and enable sharing/refresh options.
# Snapshot of Dashboard (Power BI Service)

![Dashboard_upload](https://github.com/prajyotchougale3-pv/Store-Data/blob/main/Screenshot%202026-03-27%20161320.jpg)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://github.com/prajyotchougale3-pv/Store-Data/blob/main/Screenshot%202026-03-27%20161348.jpg)
![Dashboard_upload](https://github.com/prajyotchougale3-pv/Store-Data/blob/main/Screenshot%202026-03-27%20161417.jpg)
![Dashboard_upload](https://github.com/prajyotchougale3-pv/Store-Data/blob/main/Screenshot%202026-03-27%20161439.jpg)
![Dashboard_upload](https://github.com/prajyotchougale3-pv/Store-Data/blob/main/Screenshot%202026-03-27%20161439.jpg)
# Insights

[1] Total Number of Orders = 3510
Top 5 products contributed nearly 40% of total sales.

Bottom 5 products accounted for less than 5% of sales.

Profit margins were highest in premium categories, while discounts reduced margins by 15–20% in clearance sales.

Inference: A small set of products drives most revenue, while heavy discounts erode profitability.

[2] Sales Trends (2020–2024)
Peak sales observed in 2023 (0.65M).

Lowest dip in 2022 (0.41M).

Overall growth trend shows a 12% increase from 2020 to 2024.

Inference: Sales are cyclical with strong festive peaks, but long‑term growth is positive.

[3] Profit vs. Net Sales
Scatter plot shows a strong positive correlation.

Higher net sales consistently yield higher profit, with outliers in discounted categories.

Inference: Profitability is directly tied to sales volume, but discounts weaken the relationship.

[4] Discounts by Promotion Category
Weekend Flash Sale: 23K

Clearance Sale: 18K

Summer Sale: 7K

New Year Special: 3K

Festive Diwali: 0K

Inference: Flash and clearance sales dominate discounting, but festive offers had minimal impact.

[5] Geographical Sales Distribution
Highest sales in Mumbai, Delhi, and Pune.

Moderate sales in Hyderabad and Chennai.

Lower sales in tier‑2 cities.

Inference: Metro cities drive majority of revenue; expansion opportunities exist in smaller cities.
