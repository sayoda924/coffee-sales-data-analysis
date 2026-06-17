# coffee-sales-data-analysis
Interactive Coffee Sales Dashboard built in Excel. Cleaned &amp; modeled raw transaction data using XLOOKUP and INDEX/MATCH to connect orders, 1K customers, and product catalogs. Developed Pivot Tables &amp; dynamic charts to track trends, top 5 customers, and regional sales, with Slicers/Timelines for seamless data exploration.
# Coffee Orders Sales Analysis & Interactive Dashboard

## 📌 Project Overview
This project focuses on analyzing raw sales data for a coffee business using Microsoft Excel. The objective was to transform raw transactional data into an interactive, insight-driven dashboard that helps understand customer behavior, product performance, and sales trends across different regions.

## 📊 Dataset Structure
The workbook `coffeeOrdersRaw_Data.xlsx` contains 7 dedicated sheets:
- **orders:** Transactional data containing Order IDs, Dates, Quantities, and integrated product/customer details.
- **customers:** Profile data for 1,000 customers (Names, Emails, Locations, and Loyalty Card status).
- **products:** Product catalog with details on Coffee Type (Arabica, Robusta, Excelsa, Liberica), Roast Type, Size, Unit Price, and Profit Margin.
- **DashBoard:** The main interactive interface for stakeholders.
- **Total sales / Country BarChart / Top 5:** Pivot tables and chart data backing up the visual dashboard.

## 🛠️ Advanced Excel Techniques & Formulas Used
To clean, model, and analyze the data, the following features were utilized:
- **Data Modeling & Relationships:** Connected multiple tables dynamically using advanced lookup formulas instead of static copying.
- **Advanced Formulas:**
  - `XLOOKUP`: Used to fetch customer details (Name, Email, Country) into the orders sheet.
  - `INDEX & MATCH`: Implemented to dynamically retrieve product specifications (Coffee Type, Roast, Size, Unit Price) based on multiple criteria.
  - `IF` & Nested Logic: Used for handling missing data and formatting (e.g., handling missing emails or mapping full names).
- **Data Visualization:** Built dynamic Pivot Tables and Charts (Bar charts, Line charts) to track trends.
- **Interactivity:** Added **Slicers** and **Timelines** to allow users to filter data dynamically by Date, Country, and Product Type.

## 📈 Key Insights Delivered
- **Top Performing Products:** Identified the top 5 coffee products driving the highest revenue and profit.
- **Regional Sales Distribution:** Analyzed sales across different countries (e.g., United States, Ireland) to pinpoint key markets.
- **Customer Loyalty Impact:** Evaluated sales generated from loyalty cardholders versus regular customers.

## 📷 Dashboard Preview
*(Tip: Take a screenshot of your Excel Dashboard, upload it to GitHub, and replace the link below to show your work!)*
![Dashboard Preview](images/dashboard_screenshot.png)

## 🚀 How to Explore the Project
1. Download the `coffeeOrdersRaw_Data.xlsx` file from this repository.
2. Open it using Microsoft Excel (2021 or Microsoft 365 recommended for full formula compatibility).
3. Navigate to the **DashBoard** sheet and use the interactive slicers to filter the metrics.
