# Online Store Annual Sales Report - Excel Dashboard
 
## Objective
 
An online store wanted to create an annual sales report so they can better understand their customers and grow their sales. This project answers some key business questions using data analysis done entirely in Microsoft Excel.
 
---

##Dashboard Preview :

![OSDA002](https://github.com/user-attachments/assets/50405be6-c426-48e0-ad08-c5c43ecffa39)

---
 
## What's Inside the Dashboard
 
**Order: Channels** — Pie chart showing which platforms (Amazon, Myntra, Flipkart, Ajio, Meesho, Nalli, Others) are driving the most orders. Amazon leads at 35.48%.
 
**Top 6 States by Sales** — Horizontal bar chart. Maharashtra tops the list followed by Karnataka, Uttar Pradesh, Telangana, Tamil Nadu, and Delhi.
 
**Order Status** — Pie chart showing 92% of orders were delivered successfully. Cancelled, returned, and refunded orders are minimal.
 
**Orders: Age vs Gender** — Grouped bar chart comparing Men and Women across Adult, Senior, and Youth age groups. Adult women are the biggest buyers at 34.59%.
 
**Orders & Sales** — Combo chart showing monthly sales amount (bars) and order count (line). March had the highest sales and orders.
 
**Sales: Men vs Women** — Women contributed 64% of total sales vs 36% for men.
 
---

## Tools Used
 
- Microsoft Excel
  - Pivot Tables
  - Pivot Charts
  - Slicers (Month, Channel, Category filters)
  - Dashboard layout
 
---
 
## Key Insights
 
1. **March** was the best performing month for both sales and orders
2. **Women** are buying significantly more than men (64% vs 36%)
3. **Maharashtra** is the top contributing state
4. **Amazon** is the biggest sales channel (35.48%)
5. **Adult women** are the primary customer segment
6. **92%** of all orders were delivered successfully

---

## Project Workflow
 
**1. Data Understanding**
First went through the entire dataset column by column to understand what each column means and what kind of data it holds — things like Order ID, customer name, gender, age, date, status, channel, category, amount, etc.
 
**2. Data Cleaning**
After going through the data, found a few issues and fixed them —
- Gender column had inconsistent values like "M" and "Men", "W" and "Women" — normalized all of them to just Men/Women
- Checked for blank/null rows
- Made sure the data types were correct for each column (dates as dates, amounts as numbers, etc.)
 
**3. Data Processing**
Created some new columns that were needed for analysis —
- Extracted **Month** from the date column so monthly trends could be tracked
- Created an **Age Group** column (Adult, Senior, Youth) by putting conditions on the age column using IF formula
 
**4. Data Analysis**
Used Pivot Tables to analyze the cleaned data and answer each of the business questions — monthly sales, gender comparison, state-wise performance, channel contribution, order status breakdown, and age vs gender trends.
 
**5. Data Visualization & Dashboard**
Built charts from the pivot tables and arranged them into a single interactive dashboard. Added Slicers for Month, Channel, and Category so the dashboard can be filtered dynamically.
