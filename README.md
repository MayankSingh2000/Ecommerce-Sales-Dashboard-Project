# 📊 E-Commerce Sales Analysis Dashboard | Power BI

## 📌 Project Overview
This project presents an interactive **E-Commerce Sales Dashboard built in Power BI** to analyze business performance using key metrics such as **Sales, Profit, Quantity, and Profit Margin** with **Year-over-Year (YoY) comparison**.  
The dashboard helps stakeholders monitor trends, identify top & bottom products, evaluate regional performance, and optimize shipping strategies.

---

## 🎯 Business Objectives
- Track **YTD Sales, Profit, Quantity & Profit Margin**
- Compare **current year vs previous year performance**
- Identify **top-performing and underperforming products by sales**
- Analyze **regional contribution to total revenue**
- Understand **customer shipping preferences**
- Support **data-driven business decisions**

---

## 📈 Key Insights
- **Total YTD Sales:** $11.53M (↓ 0.83% YoY)
- **Total YTD Profit:** $1.34M (↑ 4.5% YoY)
- **Total YTD Quantity:** 107.2K units (↓ 7.29% YoY)
- **Profit Margin:** 11.58% (↑ 5.37%)

### 📦 Category Performance
- **Office Supplies** is the highest revenue-generating category.
- **Furniture** shows positive growth.
- **Technology** experienced a slight YoY decline.

### 🏆 Product Performance
- **Top Product:** Staple Envelope ($57K)
- **Low Performing Products:** Eldon Jumbo ProFile Portable File Boxes Graphite/Black

### 🌍 Regional Contribution
- **West:** 32.22% (Highest)
- **East:** 28.42%
- **Central:** 23.19%
- **South:** 16.17% (Lowest)

### 🚚 Shipping Analysis
- **Standard Class:** 60.57%
- **Second Class:** 19.22%
- **First Class:** 15.10%

---

## 🛠 Tools & Technologies Used
- **Microsoft SQL Server**
- **SQL Server Management Studio**
- **Power BI**
- **Power Query (ETL)**
- **Data Modelling**
- **DAX (Data Analysis Expressions)**
- **Microsoft Excel / CSV Dataset**

---

## 🧮 Key DAX Measures Implemented
- YTD Sales
- Previous YTD Sales (PYTD)
- YoY Sales Growth %
- YTD Profit
- Profit Margin %
- YTD Quantity

---

## ✅ Features of the Dashboard
- Dynamic **segment slicer** (Consumer, Corporate, Home Office)
- **YTD vs PYTD trend analysis**
- Interactive **top & bottom product analysis**
- **Regional & shipping-based performance tracking**
- Clean and business-friendly UI

---

## 📁 Dataset Information

This project uses two primary datasets which were first imported to **SQL Server Management Studio** and then to **Power BI** for analysis and visualization:

### 1️⃣ `ecommerce_data.csv`
This dataset contains detailed transactional data of the e-commerce business. It is used for calculating sales performance, profitability, product trends, and customer behavior.

**Key Columns Include:**
- Order ID  
- Order Date  
- Ship Date  
- Customer ID  
- Customer Segment (Consumer, Corporate, Home Office)  
- Product ID  
- Product Name  
- Category (Office Supplies, Furniture, Technology)  
- Sub-Category  
- Sales  
- Quantity  
- Discount  
- Profit  
- Shipping Mode  
- Region  
- State  

**Usage in Dashboard:**
- YTD Sales, Profit, Quantity & Profit Margin
- YoY Growth Analysis
- Top 5 & Bottom 5 Products
- Category-wise Performance
- Shipping Mode Analysis
- Segment-based Filtering

---

### 2️⃣ `us_state_long_lat_codes.csv`
This dataset contains geographic mapping information for U.S. states and is used for spatial visualization in the dashboard.

**Key Columns Include:**
- State Name  
- State Code  
- Latitude  
- Longitude  

**Usage in Dashboard:**
- Sales by State Map Visualization  
- Regional Sales Distribution  
- Geographic Demand Insights  

---

✅ These datasets were cleaned and transformed using **Power Query**, and business logic was implemented using **DAX** for accurate time intelligence and KPI calculations.

---

## 🚀 How to Use
1. Download the `.pbix` file from this repository.
2. Open with **Power BI Desktop**.
3. Refresh the dataset.
4. Use slicers and filters for interactive analysis.

---

## 👤 Author
**Mayank Singh** 
-- Aspiring Data Analyst
-- Skilled in SQL,Power BI and Excel
--- Actively seeking entry-level Data Analyst opportunities


