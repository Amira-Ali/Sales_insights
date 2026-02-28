# Sales Insights Dashboard

Power BI sales dashboard providing internet sales insights for a business owner, built on Microsoft's AdventureWorksDW2019 sample database.

## 🎯 Client Requirements
- Internet sales by product
- Internet sales by customer
- Internet sales over time
- Sales vs budget comparison

## 📊 Dashboard Pages

**Sales Overview**
![Sales Overview](sales_overview.png)
![Sales Overview](sales_overview.png)

**Sales by Customers**
![Sales by Customers](sales_by_customers.png)

**Sales by Products**
![Sales by Products](sales_by_products.png)

---

## 🔗 Live Dashboard
[View on Power BI](https://app.powerbi.com/links/Yugs1wefWC?ctid=84008d0f-90f6-4e21-b588-403ad5bfdd2f&pbi_source=linkShare)

## 🛠️ Tools Used
- SQL Server (data cleaning & transformation)
- Microsoft Excel (budget data)
- Power BI (DAX, measures, map visuals, product images)

## 📂 Data Sources
- [AdventureWorksDW2019](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure) — main database
- Client-provided Excel budget file (2 years)

## 📝 Notes
- Sales employee analysis was excluded — employees work in physical stores, not online.
- Product images were loaded directly from SQL Server into Power BI to preserve binary data.
- Guided by [Ali Ahmad](https://github.com/aliahmad-1987)
