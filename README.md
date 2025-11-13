# 🌿 Plant Co. Performance Dashboard (Power BI)

Interactive Power BI dashboard for analyzing Year-to-Date (YTD), Prior Year-to-Date (PYTD), and Gross Profit Percentage (GP%) performance across countries, products, and time periods.

**Live Demo:** *(Add Power BI link once published)*  

---

## 🎯 Highlights

* **Dashboard Focus:** Gross Profit Performance (2023–2024)
* **KPIs:** YTD Gross Profit, PYTD Gross Profit, YTD vs PYTD Difference, GP%
* **Visuals:**
  * Waterfall Chart — Gross Profit YTD vs PYTD by Month, Country, and Product  
  * Treemap — Bottom 10 Countries by YTD vs PYTD  
  * Line & Stacked Column Chart — Gross Profit by Month and Product Type  
  * Scatter Plot — Account Profitability by Value YTD and GP%  
  * KPI Cards — YTD, PYTD, YTD vs PYTD, and GP%  

* **Interactivity:**
  * Slicers for **Year (2023 / 2024)**  
  * **Cross-filtering** across all visuals for unified dashboard interaction  
  * **Drill-through** on the waterfall chart to view product and product-type details  

* **Comparisons:** Real-time variance tracking between YTD and PYTD across all countries and product types  
* **Design:** Clean layout, consistent color theme for increase/decrease values, and clear profitability segmentation  

---

## 📁 Repository Structure

```
.
├── README.md
├── PlantCo.pbix
└── Plant_DTS.xsl
```

---
## 🚀 Quickstart

1. **Clone** this repo  
2. Open `Plant.pbix` in **Power BI Desktop**  
3. If needed, update the Excel data source path under **Transform Data → Data Source Settings**  
4. Refresh data and publish to **Power BI Service**  
5. Add your published link to the **Live Demo** section above  

---

## 🔧 Features in Detail

### KPI Cards
* YTD Gross Profit, PYTD Gross Profit, YTD vs PYTD Difference, and GP%  
* Each card dynamically updates based on filters and slicers  

### Waterfall Chart
* Visualizes gross profit increase/decrease by month and country  
* **Drill-through** to product type and product-level performance  

### Treemap
* Displays bottom 10 countries by YTD vs PYTD variance  
* Helps identify underperforming markets for improvement  

### Line & Stacked Column Chart
* Tracks monthly and quarterly profit trends by product type  
* Highlights seasonal patterns and overall business performance  

### Scatter Plot
* Segments accounts by GP% and YTD value for profitability analysis  
* Useful for identifying high-value or low-margin customers  

---

## 💡 Key Takeaways

* 📊 **Track profit performance and YoY comparisons**  
* 🌍 **Identify underperforming countries and accounts**  
* 📈 **Visualize trends across products, categories, and time**  
* ⚡ **Interactive, filterable dashboards for quick decision-making**  

---

## 🗂 Data Source
- Excel-based dataset containing sales, product, and regional performance data  
- Includes date, product type, account, and gross profit fields for multi-dimensional analysis  

---

## 🔮 Future Improvements
- Integrate with **SQL database** for automated data refresh  
- Add **forecasting visuals** for future profit projection  
- Implement **dynamic tooltips** and annotations for better insights  
- Expand analysis to include **sales and quantity KPIs**  

---

## 💼 Business Value
- Quickly pinpoint regions and products impacting profit performance  
- Support strategic planning and performance optimization  
- Enable business leaders to monitor profitability trends with clarity and precision  

