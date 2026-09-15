# RetailMart-PowerBI-Sales-Dashboard
Interactive RetailMart sales and customer insights dashboard built with Microsoft Power BI and DAX using 75K+ sales records from 2023–2025.

# RetailMart – Power BI Sales & Customer Insights Dashboard
An interactive **Power BI dashboard** created to analyze RetailMart's sales, profitability, products, customers, channels, categories, and regional performance.

The project uses approximately **75,000 sales records from 2023–2025** and converts raw retail data into interactive KPIs and visual insights.

## 📊 Project Overview

The dashboard is divided into two pages:

### 1. Executive Sales Overview

This page provides a high-level view of overall business performance.

#### KPI Cards
- **Total Sales:** ₹351.34M
- **Total Profit:** ₹123.55M
- **Total Orders:** 75K
- **Total Customers:** 12K
- **Profit Margin:** 35.17%

#### Charts
- **Monthly Sales Trend** – shows how sales change month by month.
- **Sales by Category** – compares sales across different product categories.
- **Profit by Region** – compares profit generated across regions.
- **Sales by Channel** – compares Online and Store sales.

#### Interactive Filters
- Year
- Region
- Category
- Channel

### 2. Product & Customer Insights

This page provides a more detailed analysis of products and customers.

#### Charts
- **Top 10 Products by Sales** – identifies the products generating the highest sales.
- **Sales by Sub-Category** – compares sales across different sub-categories.
- **Top 10 Customers by Sales** – identifies high-value customers based on sales contribution.
- **Sales by Age Group** – shows sales distribution across different customer age groups.

Customer IDs are used as the unique customer identifier, while customer names can be viewed through tooltips.

## 🗂️ Dataset

- **Records:** Approximately 75,000
- **Time Period:** 2023–2025
- **Source Format:** Excel
- **Data Type:** Fictional retail sales data created for academic analysis

### Main Fields
- Order_ID
- Order_Date
- Customer_ID
- Customer_Name
- Gender
- Age
- City
- State
- Region
- Product_ID
- Product_Name
- Category
- Sub_Category
- Quantity
- Unit_Price
- Discount
- Sales
- Cost
- Profit
- Channel
- Payment_Mode
- Rating

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **DAX (Data Analysis Expressions)**
- **Microsoft Excel**

## 📐 DAX Measures

`` DAX        
Total Sales = SUM(Sales_Data[Sales])

Total Profit = SUM(Sales_Data[Profit])

Total Orders = DISTINCTCOUNT(Sales_Data[Order_ID])

Total Customers = DISTINCTCOUNT(Sales_Data[Customer_ID])

Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)

An Age Group calculated column was also created for customer segmentation.

💡 Key Insights
- RetailMart generated ₹351.34M in total sales and ₹123.55M in total profit.
- The overall profit margin is 35.17%.
- The dashboard helps compare monthly sales performance across the year.
- Online sales contribute 57.73%, while Store sales contribute 42.27%.
- Product-level analysis identifies the top-selling products and sub-categories.
- Customer-level analysis identifies high-value customers based on sales.
- Age-group analysis provides a view of sales contribution across customer segments.
- Regional analysis helps compare profitability across different regions.

📸 Dashboard Screenshots
Executive Sales Overview

Product & Customer Insights

🎯 Business Use

This dashboard can help a business:

Monitor sales and profitability.
Identify high-performing products and categories.
Compare Online and Store sales.
Identify high-value customers.
Understand customer age-group performance.
Compare regional profitability.
Support data-driven business decisions.

📁 Project Structure
RetailMart-PowerBI-Sales-Dashboard/
│
├── README.md
├── RetailMart_PB_Project.pbix
├── dataset/
│   └── RetailMart_75K_Clean_PowerBI_Dataset.xlsx
│
└── screenshots/
    ├── overview.png
    └── product-customer-insights.png


👨‍💻 Author
Harsh Rana

Academic Power BI / Business Intelligence Project
