AdventureWorks Sales Analysis – Power BI Project

Project Overview
This Power BI project analyzes AdventureWorks sales data across multiple years to understand
sales trends, profit performance, customer behavior, and regional performance.

---

Tools Used
- Power BI
- Power Query
- DAX
- CSV datasets

---

Datasets Used
#Sales Data
- Sales_2020.csv
- Sales_2021.csv
- Sales_2022.csv

#Lookup Tables
- Calendar
- Customer
- Product
- Product Category
- Product Subcategory
- Territory
- Returns

---

Dashboard Features
- Total Sales, Profit, Quantity KPIs
- Year-wise and Month-wise sales trends
- Top products and categories
- Regional sales performance
- Return rate analysis
- Interactive slicers (Year, Region, Category)

---

Data Model
A star schema data model was used:
- Fact Table: Sales Data
- Dimension Tables: Product, Customer, Calendar, Territory

A SnowFlake schema data model was used:
-Dimension Tables: Product, Customer, Calendar, Territory
-Sub Dimension Tables: Product Category, Product Sub-Category

---

How to Use
1. Download the repository
2. Open `PowerBI_File/AdventureWorks_Sales_Analysis.pbix`
3. If prompted, update dataset file paths

---

Dashboard Preview
Screenshots are available in the `Screenshots/` folder.

---

Author
**Bhuvanadurai M**  
GitHub: https://github.com/BhuvanaduraiMK
