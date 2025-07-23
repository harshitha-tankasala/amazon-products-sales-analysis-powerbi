# 📦 Amazon Products Sales Analysis Dashboard

A comprehensive Power BI dashboard to analyze sales performance of Amazon products by category, time period, and top-performing SKUs. This visualization helps stakeholders identify trends, seasonal behavior, and product demand across various metrics.

---

## 📑 Table of Contents
- [Project Overview](#project-overview)
- [Dashboard Overview](#dashboard-overview)
- [Objectives](#objectives)
- [Key Features](#key-features)
- [KPIs Tracked](#kpis-tracked)
- [Visualizations](#visualizations)
- [Tools & Technologies](#tools--technologies)
- [Challenges & Solutions](#challenges--solutions)
- [Outcomes](#outcomes)
- [Skills Demonstrated](#skills-demonstrated)
- [How to Run the Dashboard](#how-to-run-the-dashboard)
- [License](#license)

---

## 🚀 Project Overview
This project provides a sales-driven insight into Amazon product performance using Power BI. It helps in tracking sales by category, monthly/weekly trends, and customer review patterns, thereby aiding strategic planning and market targeting.

---

## 📊 Dashboard Overview
![Dashboard Screenshot](./Screenshot%202025-07-23%20054835.png)

The dashboard includes dynamic filtering and comparative sales analysis between Year-To-Date (YTD) and Quarter-To-Date (QTD) periods across different product categories.

---

## 🎯 Objectives
- Monitor total sales, product movement, and review volumes.
- Identify top-performing categories and products.
- Spot seasonal or periodic trends in consumer behavior.
- Enable data-informed decisions for inventory and marketing.

---

## 🔍 Key Features
- Interactive slicers for filtering by **Product Category** and **Quarter**.
- Real-time comparison of **YTD** vs **QTD** sales.
- Weekly and monthly trend visualizations.
- Highlight of best-selling and most-reviewed products.

---

## 📌 KPIs Tracked
- **YTD Sales**: $2.18M  
- **QTD Sales**: $811.09K  
- **YTD Products Sold**: 27.75K  
- **YTD Reviews**: 19.42M  
- **% YTD by Category**
- **Top 5 Products by Sales & Reviews**

---

## 📈 Visualizations
- **Line Chart**: Monthly sales trends.
- **Bar Chart**: Weekly sales visualization.
- **Matrix Table**: Sales breakdown by product category.
- **Horizontal Bar Charts**:
  - Top 5 Products by YTD Sales.
  - Top 5 Products by YTD Reviews.
- **Slicers** for interactive filtering by category and quarter.

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **Power Query** for ETL and transformations
- **DAX** for KPIs and calculated metrics
- **Excel / CSV** files for input datasets

---

## ⚠️ Challenges & Solutions
| Challenge                          | Solution                                                             |
|-----------------------------------|----------------------------------------------------------------------|
| Quarter-wise comparisons          | Created dynamic QTD measures using DAX                               |
| High cardinality in product names | Applied top-N filters with rank logic to show only top products      |
| Visual clarity on large datasets  | Used slicers and tooltips for improved interactivity and filtering   |

---

## ✅ Outcomes
- Clear understanding of revenue distribution by category.
- Ability to forecast and plan inventory per quarter.
- Identified products with high review-to-sales ratio for feedback analysis.

---

## 🧠 Skills Demonstrated
- Power BI data modeling and design  
- Advanced DAX for dynamic calculations  
- ETL and data shaping in Power Query  
- Business performance analysis  
- Sales & product trend interpretation

---

## ▶️ How to Run the Dashboard
1. Clone or download this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Interact with slicers to explore filtered insights.
4. Connect your own dataset (optional) through "Transform Data" > "Edit Queries".

📁 **Download dataset**: [Click here](./data/amazon_products_sales.csv)

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).
