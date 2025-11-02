# 📊 Superstore Sales Analysis (Excel)

**Author:** Hemang Chaudhary  
**Tools Used:** Microsoft Excel (PivotTables, Slicers, Conditional Formatting)  
**Dataset:** [Superstore Dataset – Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)  

---

## 🧠 Project Overview
This project analyzes the **Superstore dataset** to uncover insights about sales performance, product profitability, discount impact, and customer behavior between **2014–2017**.  
The analysis was performed entirely in **Excel**, featuring **data cleaning**, **KPI calculations**, **PivotTable analysis**, and **interactive dashboards** with slicers for year-based filtering.

---

## 🎯 Objectives
The goal was to analyze sales, profit, and customer trends to identify:
- Which **regions, states, and categories** drive the most sales and profit  
- Which **products** are most and least profitable  
- How **discounts** affect profitability  
- Which **customer segments** bring the most revenue  
- How **sales and profit** evolve over time  

---

## 💡 Key Analytical Insight: Discount Profitability

The analysis revealed that discounts are the single largest driver of negative profit margin. The primary actionable insight is the clear threshold for when discounts transition from driving lower margin sales to causing significant losses.

| Discount Range | Total Profit | Profit Margin (%) |
|:---|:---|:---|
| 0% | **+\$320,987.60** | **29.51%** |
| 10% - 20% | **+\$10,448.17** | **12.75%** |
| 20% - 30% | **+\$90,337.31** | **11.82%** |
| **30% - 40%** | **-\$12,748.36** | **-10.86%** |
| **40% - 50%** | **-\$25,550.16** | **-20.96%** |
| **> 50%** | **-\$97,065.48** | **-78.82%** |

**Conclusion:** The Superstore must re-evaluate any discount policy that authorizes discounts **above 20%**, as these ranges are directly responsible for the majority of the company's losses.

---

## 🧹 Data Cleaning & Preparation
Steps performed in Excel:
1. **Converted dates** to proper Excel date format and extracted **Year, Month, and Day of Week**.  
2. Added helper columns:
   - `Profit Margin` = `Profit / Sales`
   - `Discount Range` using nested IF formulas  
   - `Shipping Days` = `Ship Date – Order Date`
   - `Distinct Customer Flag` (1 per unique customer per year)
3. Categorized discounts data into a discount range column for focused analysis.  
4. Removed blank or duplicate entries and standardized category and subcategory names.

---

## 📊 Analyses

### 🏷️ **Sales Analysis**
- KPI cards showing Total Sales, Total Profit, Profit Margin and YoY Growth
- Yearly Sales and Profit trends (with variance from previous year)
- Total Profit Margin by Year
- Sales and Profit by Region
- Top 10 States by Sales and Profit
- Top 5 States by Profit Margin / Loss Margin

### 📦 **Product Analysis**
- Sales by Product Category
- Profit and Profit Margin by Product Category
- Top 10 Selling Products (by Sales & Volume)
- Top 10 Most Profitable Products

### 👥 **Customer Analysis**
- Total Customers by Year
- Sales, Profit and Profit Margin by Customer Segment
- Top 3 Customers leaderboard  
- Total Orders by Month, Year, and Day of Week
- Average Order Value
- Average Shipping Time by Ship Mode

All PivotTables are **linked to a Year slicer** for interactive filtering.

Each dashboard is dynamic, using slicer for **Year** filter, with unified fonts and color themes.

---

## 📏 Key Metrics & KPIs
| Metric | Description |
|--------|--------------|
| **Total Sales** | Overall revenue |
| **Total Profit** | Total profit earned |
| **Profit Margin** | Profit as % of sales |
| **Average Order Value (AOV)** | Sales per order |
| **Distinct Customers (per Year)** | Unique customers by year |
| **Top 3 Customers Leaderboard** | Top 3 customers by year with the largest sales amount |

---

## 🪄 Tools & Skills Demonstrated

1. Excel Data Cleaning
2. Data Modeling with Helper Columns
3. Pivot Tables & Charts
4. Slicers and Interactive Dashboards
5. Conditional Formatting for Profit/Loss Visualization
6. Analytical Storytelling through Dashboards

---

## 📬 Contact
**Author:** Hemang Chaudhary

**[LinkedIn](https://www.linkedin.com/in/hemangchaudhary)**
