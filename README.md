# Coffee-Sales-Dashboard

### Project Overview
Coffee Sales Dashboard A visually interactive dashboard built to analyze coffee sales data. Features include sales trends, top-performing products, customer insights, and regional performance. Ideal for business intelligence and actionable insights. Developed using Excel

### Data Sources
coffeeOrdersData.xlsx (https://github.com/mochen862/excel-project-coffee-sales)

### Tools
Microsoft Excel

### KPI’s
- Sales (over time,roast type, loyalty card, packaging size)
- Best Customers (over time, roast type,packaging  size, loyalty card)
- Sales by country (over time,roast type,packaging size, loyalty card)

### Procedure
#### 1. Add missing columns to order sheet
- Customer Name, Email, Country (XLOOKUP)
- Coffee Type, Roast Type, Size, Unit Price (Index Match)
- Sales (multiple)
- Coffee Type Name (IF Formula)
- Date and Size (Customize Format)
#### 2. Check for duplicates
#### 3. Create Pivot Chart line graph (Total Sales Over Time)
- create pivottable: rows: order date (rows:Years(Order Date), Months (Order Date);column: coffee type name;Values: Sales)
- insert pivot chart
- insert time line
- insert slizer
- adjust design
#### 4. Create Bar Chart (Sales by Country)
- duplicate previous scheet
- change pivot table (rows: country;values: sum of sales) 
- insert bar chart (asc by sum of sales)
- adjust design
#### 5. Create Bar Chart (Top 5 Customers)
- duplicate previous sheet
- change pivot table (rows: customer name;values: sum of sales)
- filter top customers
#### 6. Create Dashboard
- open new sheet
- create header (insert shape, name dashboard)
- insert charts
- adjust 
- report connection, so timeline, slizer and charts are connected


