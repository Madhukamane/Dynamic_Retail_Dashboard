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
| Column Name   | Data Type     | Description | Primary Key |
|---------------|---------------|-------------|-------------|
| Customer Name | Text          | Full name of the customer | No |
| Segment       | Text          | Customer segment (e.g., Consumer, Corporate, Home Office) | No |
| City          | Text          | City of the customer | No |
| State         | Text          | State/Province of the customer | No |
| Country       | Text          | Country of the customer | No |
| Postal Code   | Whole Number  | Postal code (missing/null replaced with -1) | No |
| Market        | Text          | Geographic market (e.g., US, APAC, EU) | No |
| Region        | Text          | Sub-region within the market | No |
| Product ID    | Text          | Unique identifier for the product | Yes |
| Category      | Text          | Product category (e.g., Technology, Furniture) | No |
| Sub-Category  | Text          | Sub-category of the product | No |
| Product Name  | Text          | Full name/description of the product | No |
| Sales         | Decimal       | Sales revenue generated from the order | Yes |
| Quantity      | Whole Number  | Quantity of items ordered | Yes |
| Discount      | Decimal       | Discount applied to the order | Yes |
| Profit        | Decimal       | Profit earned on the order | Yes |
| Shipping Cost | Decimal       | Cost of shipping the order | Yes |
| Order Priority| Text          | Priority of the order (e.g., Critical, Medium) | No |

--- 

## ❓ Problem Statements Solved
This dashboard answers the following business questions:  

1. **KPIs** – Total Sales, Profit, Quantity, Number of Orders, Profit Margin
<img width="525" height="78" alt="image" src="https://github.com/user-attachments/assets/b5d8c7db-c34b-4e8a-9008-a411ddeb9066" />


2. **Sales & Profit Analysis** – Relationship between sales and profitability  
<img width="291" height="231" alt="image" src="https://github.com/user-attachments/assets/883416be-0f34-482e-81db-f8ffd78beba4" />


3. **Category-Wise Profit** – Which categories are most/least profitable  
<img width="270" height="217" alt="image" src="https://github.com/user-attachments/assets/aa6ef0c2-e354-4c54-9df3-742d5fefaa0b" />


4. **Segment-Wise Sales Share (%)** – Revenue contribution by segment  
<img width="271" height="215" alt="image" src="https://github.com/user-attachments/assets/165671be-9aad-40ec-a4ea-bcc2eb52d5a6" />


5. **Sales by Country** – Identify top-performing regions and countries  
<img width="292" height="217" alt="image" src="https://github.com/user-attachments/assets/6f619a08-e7a8-447c-9dcd-9034b3096858" />


6. **Top 5 Sub-Categories** – Best-performing sub-categories  
<img width="260" height="233" alt="image" src="https://github.com/user-attachments/assets/c02a0d68-c473-4ca4-a41d-29ad43828bd3" />


7. **Bottom 5 Sub-Categories** – Least-performing sub-categories  
<img width="267" height="223" alt="image" src="https://github.com/user-attachments/assets/b78e2029-3135-471e-a4fb-a628f89db4b2" />


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
<img width="1082" height="666" alt="image" src="https://github.com/user-attachments/assets/7169480f-3adf-48f4-bed8-59d1a0502b7d" />


---



⭐ If you found this project useful, don’t forget to **star the repo**!
