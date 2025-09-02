# 📊 Dynamic Retail Dashboard – Walmart Dataset (Excel)

## 📝 Project Overview
This project delivers a **dynamic retail dashboard in Excel** built using Walmart’s sales dataset.  
The dashboard consolidates data from **Orders, People, and Returns** tables into interactive visualizations that enable Walmart to identify **sales trends, profit drivers, and customer behavior patterns**.  

It uses **Excel (Power Query, Pivot Tables, Charts, Slicers)** to perform **Exploratory Data Analysis (EDA)** and design an interactive dashboard.

---

## 🎯 Objective
The objective of this project is to:
- Track **Key Performance Indicators (KPIs)** at a glance
- Explore **sales & profit analysis** across categories and sub-categories
- Understand **customer segment sales share**
- Visualize **sales across regions & countries**
- Highlight **top and bottom performing sub-categories**
- Analyze **yearly sales trends** for growth patterns

By doing so, Walmart can **optimize its operations** and make better business decisions.

---

## 📂 Dataset
The dataset is hosted on GitHub and loaded into Excel via Power Query.  

📎 [Dataset Link](https://github.com/Madhukamane/Dynamic_Retail_Dashboard/blob/main/dynamic_retail_dashboard.xlsx)

### Data Tables:
1. **Orders** – Transaction details (sales, profit, discounts, shipping, category, etc.)  
2. **People** – Region assigned to salespeople  
3. **Returns** – Records of returned orders  

### Sample Records

**Orders**
| Product ID | Category    | Sub-Category | Product Name | Sales  | Quantity | Discount | Profit | Shipping Cost | Order Priority |
|------------|-------------|--------------|--------------|--------|----------|----------|--------|---------------|----------------|
| TEC-AC-10003033 | Technology | Accessories | Plantronics Wireless Headset | 2309.65 | 7 | 0 | 762.18 | 933.57 | Critical |
| FUR-CH-10003950 | Furniture  | Chairs       | Novimex Leather Armchair    | 3709.39 | 9 | 0.1 | -288.76 | 923.63 | Critical |

**People**
| Person          | Region  |
|-----------------|---------|
| Anna Andreadi   | Central |
| Kelly Williams  | East    |

**Returns**
| Returned | Order ID      | Market   |
|----------|---------------|----------|
| Yes      | MX-2013-168137 | LATAM    |
| Yes      | US-2011-165316 | LATAM    |

---

## 📖 Data Dictionary
| Column          | Type     | Description                                    |
|-----------------|----------|------------------------------------------------|
| Customer Name   | Text     | Full name of the customer                      |
| Segment         | Text     | Customer segment (Consumer, Corporate, etc.)   |
| Country         | Text     | Country of the customer                        |
| Market          | Text     | Geographic market (US, APAC, EU, LATAM, etc.)  |
| Region          | Text     | Sub-region within the market                   |
| Product ID      | Text     | Unique identifier for the product              |
| Category        | Text     | Product category (Technology, Furniture, etc.) |
| Sub-Category    | Text     | Product sub-category                           |
| Sales           | Decimal  | Sales revenue generated                        |
| Quantity        | Integer  | Quantity of items ordered                      |
| Discount        | Decimal  | Discount applied                               |
| Profit          | Decimal  | Profit earned on the order                     |
| Shipping Cost   | Decimal  | Shipping charges                               |
| Order Priority  | Text     | Order urgency (Critical, Medium, etc.)         |

--- 

## ❓ Problem Statements Solved
This dashboard answers the following business questions:  

1. **KPIs** – Total Sales, Profit, Quantity, Number of Orders, Profit Margin  
2. **Sales & Profit Analysis** – Relationship between sales and profitability  
3. **Category-Wise Profit** – Which categories are most/least profitable  
4. **Segment-Wise Sales Share (%)** – Revenue contribution by segment  
5. **Sales by Country** – Identify top-performing regions and countries  
6. **Top 5 Sub-Categories** – Best-performing sub-categories  
7. **Bottom 5 Sub-Categories** – Least-performing sub-categories  
8. **Yearly Sales Trend** – Growth patterns across years  

---

## 📊 Dashboard KPIs
The following KPIs are displayed at the top of the dashboard for quick insight:

| KPI                | Description       | Symbol |
|--------------------|-------------------|--------|
| Total Sales        | Sum of Sales      | 📈 |
| Total Profit       | Sum of Profit     | 💰 |
| Total Quantity     | Sum of Quantity   | 📦 |
| Total Orders       | Count of Order ID | 🛒 |
| Profit Margin      | Profit ÷ Sales    | 🔍 |

---

## 📈 Dashboard Features

### 1. **Overall KPIs**
At-a-glance view of sales, profit, quantity, orders, and profit margin.

### 2. **Sales & Profit Analysis**
- Visual comparison of **total sales vs. total profit** across categories.
- Helps identify where high sales do not translate into profitability.

### 3. **Category-wise Profit**
- Breakdown of profits across **Furniture, Office Supplies, and Technology**.
- Pinpoints the most and least profitable categories.

### 4. **Segment-wise Sales Share %**
- Pie/Donut chart showing sales distribution across **Consumer, Corporate, and Home Office** segments.

### 5. **Sales by Country**
- Country-level analysis to understand geographic contribution to revenue.

### 6. **Top 5 Sub-Categories**
- Bar chart highlighting the **best-performing sub-categories** in terms of sales/profit.

### 7. **Bottom 5 Sub-Categories**
- Identifies the **weakest sub-categories** with low or negative profitability.

### 8. **Yearly Sales Trend**
- Line/column chart showing how sales evolved over multiple years.
- Useful for identifying **seasonality or growth trends**.

---

## 🛠️ Tools & Skills Used
- **Microsoft Excel**
  - Power Query (data loading & transformation)
  - Pivot Tables & Pivot Charts
  - Slicers & Filters
  - Conditional Formatting
  - Dashboard Design
- **GitHub** (dataset hosting, version control, documentation)

---

## 🔍 Insights & Recommendations
- **Technology** is the top-performing category by sales, but some sub-categories show negative profit due to discounts.  
- **Consumer Segment** contributes the largest share of sales, suggesting strong B2C opportunities.  
- **Profit margin is highly impacted by discounts**—strategic adjustments could increase profitability.  
- **Bottom 5 sub-categories** consistently underperform; reevaluating these products could optimize inventory and focus.  

---

## 🚀 How to Use
1. Clone this repository or download the Excel file:  
   👉 [dynamic_retail_dashboard.xlsx](https://github.com/Madhukamane/Dynamic_Retail_Dashboard/blob/main/dynamic_retail_dashboard.xlsx)
2. Open the file in Microsoft Excel.
3. Navigate to the **Dashboard** sheet.
4. Use **slicers** to interactively filter by region, year, category, or segment.

---

## 🖼️ Dashboard Preview
👉 *(Add screenshots of your Excel dashboard here – e.g., KPI section, charts, slicers)*  

---



⭐ If you found this project useful, don’t forget to **star the repo**!
