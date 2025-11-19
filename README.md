# 📊 Adventure Works Analytics Dashboard (Power BI)

![Power BI](https://img.shields.io/badge/Power%20BI-Business%20Intelligence-F2C811?logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Data%20Modeling-0078D4?logo=microsoft)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Preparation-5E5E5E?logo=powerquery)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

An interactive **Adventure Works Analytics Dashboard** built in **Power BI**, delivering insights into sales, profit, targets, regions, product categories, and performance against goals.  
This project demonstrates strong skills in **data modeling**, **DAX**, **time-intelligent analysis**, and **dashboard design**.

---

## 🚀 Dashboard Features

- **KPI Multi-Row Card**  
  - Total Sales  
  - Target  
  - Variance  
  - Variance Margin  

- **Sales vs. Profit Margin Over Time**  
  - Combo chart showing:
    - **Sales** (column)  
    - **Profit Margin** (line)  
    - Across **Date.Month**

- **Regional Sales Breakdown**  
  - Column chart by:
    - **Region Group**  
    - **Product Category**

- **Quantity Sold by Product Category**  
  - Bar chart showing:
    - **Category** vs **Quantity Sold**

- **Target vs. Actual Performance**  
  - Clustered bar/column charts comparing:
    - **Sales**  
    - **Targets.Target**  
    - Across **Date.Month**

- **Financial Performance Table (Pivot)**  
  - Fiscal Year → Quarter → Month  
  - Includes:
    - Sales Orders  
    - Sales  
    - Cost  
    - Profit  
    - Profit Margin  

- **Interactive Slicers**  
  - Fiscal Year  
  - Region  
  - More Year/Region filters for synced cross-filtering  

---

## 🧠 Skills Demonstrated

### **Data Modeling**
- Built a structured star schema including:
  - **Date**, **Region**, **Product**, **Sales**, and **Targets**
- Configured relationships enabling accurate cross-filtering and time intelligence.

### **DAX & Measures**
- Key measures used:
  - `Sum(Sales.Sales)`  
  - `Sum(Sales.Cost)`  
  - `Sales.Profit`  
  - `Sales.Profit Margin`  
  - `Targets.Target`, `Targets.Variance`, `Targets.Variance Margin`
- Implemented:
  - **Month-level trend analysis**  
  - **Fiscal calendar hierarchy** (Year → Quarter → Month)  
  - **Variance metrics** for target tracking  

### **Visualization & Design**
- Dashboard includes:
  - Combo charts  
  - Column & bar charts  
  - Multi-row KPI cards  
  - Pivot tables  
  - Slicers for Year and Region  
- Prioritized:
  - Clear layout  
  - Consistent color palette  
  - Business-ready formatting  

---

## 🎯 Key Insights

- **Sales vs Target Performance:**  
  Monthly charts reveal whether the business is consistently hitting, exceeding, or missing targets.

- **Profitability Trends:**  
  The combo chart shows periods where **profit margin diverges from sales**, signaling margin pressure or efficiency gains.

- **Regional Performance Variation:**  
  Sales differ significantly by **Region Group**, with strong category-based variation visible in the regional column chart.

- **Product Category Volume Leaders:**  
  Clear identification of which product categories drive **quantity sold**, supporting operational and inventory decisions.

- **Full Fiscal View:**  
  The pivot table provides a detailed multi-level breakdown across the fiscal hierarchy, showing key financial metrics over time.

---
