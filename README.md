# 📊 Online Sales Data Analysis Dashboard

<p align="center">

**Interactive Business Intelligence Dashboard | Power BI | SQL | Excel | Power Query | DAX**

</p>

<p align="center">

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)](https://powerbi.microsoft.com/)
[![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge\&logo=postgresql\&logoColor=white)](https://www.w3schools.com/sql/)
[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge\&logo=microsoft-excel\&logoColor=white)](https://www.microsoft.com/microsoft-365/excel)
[![Power Query](https://img.shields.io/badge/Power%20Query-742774?style=for-the-badge)](https://learn.microsoft.com/power-query/)
[![DAX](https://img.shields.io/badge/DAX-Data%20Analysis%20Expressions-107C41?style=for-the-badge)](https://learn.microsoft.com/dax/)

</p>

---

## 📌 Project Overview

**Online Sales Data Analysis Dashboard** is an interactive **Business Intelligence project built using Microsoft Power BI** to analyze online retail sales performance.

The dashboard transforms raw online sales transaction data into meaningful business insights through:

* Data Cleaning
* Data Transformation
* Data Modeling
* DAX Calculations
* KPI Analysis
* Interactive Visualizations
* Sales & Profit Analysis

The dashboard provides stakeholders with a **single source of truth** for monitoring sales performance and identifying growth opportunities.

---

# 🎯 Project Objective

The primary objective of this project was to help business stakeholders monitor and analyze:

* 💰 **Sales Performance**
* 📈 **Profit**
* 🛒 **Orders**
* 📊 **Profit Margin**
* 🏷️ **Product Category Performance**
* 🌍 **Geographical Performance**
* 📅 **Monthly & Seasonal Trends**
* 🏆 **High-Performing Areas**
* ⚠️ **Underperforming Areas**

The insights can support better decisions related to **marketing, sales strategy, inventory planning and regional growth**.

---

# 🏢 Business Problem

Online retail businesses generate large amounts of transaction data, making it difficult to identify important performance trends using raw datasets.

The business required an interactive dashboard that could answer questions such as:

```text
Which product category generates the highest profit?
              ↓
Which states are performing best?
              ↓
Which cities generate the most profit?
              ↓
Which months have the highest profitability?
              ↓
Which categories require improvement?
```

Power BI was used to convert the raw transactional data into an interactive analytical solution.

---

# 📊 Dataset

### Data Source

A simulated dataset representing **online sales transactions for a retail company in India**.

### Key Fields

#### 🛒 Order Details

* Order ID
* Order Date
* Customer ID

#### 📦 Product Details

* Category
* Sub-Category
* Product

#### 🌍 Geographic Details

* State
* City

#### 💰 Sales & Profit Details

* Sales
* Quantity
* Profit

### Product Categories

```text
Clothing
Electronics
Furniture
```

### Example Sub-Categories

```text
Saree
Phones
Chairs
```

---

# 📁 Dataset Files

The project uses the following CSV datasets:

* **Orders.csv**
* **Details.csv**

> Make sure these files exist in the repository before publishing the README links.

---

# 🔄 Data Analytics Workflow

```text
              RAW SALES DATA
                    │
                    ▼
          ┌──────────────────┐
          │   CSV Datasets   │
          │ Orders + Details │
          └────────┬─────────┘
                   │
                   ▼
          ┌──────────────────┐
          │  Power Query     │
          │ Data Cleaning    │
          │ Transformation   │
          └────────┬─────────┘
                   │
                   ▼
          ┌──────────────────┐
          │  Data Modeling   │
          │   Star Schema    │
          └────────┬─────────┘
                   │
                   ▼
          ┌──────────────────┐
          │ DAX Calculations │
          │ KPI Development  │
          └────────┬─────────┘
                   │
                   ▼
          ┌──────────────────┐
          │ Power BI         │
          │ Dashboard        │
          └────────┬─────────┘
                   │
                   ▼
          BUSINESS INSIGHTS
```

---

# 🧹 Data Cleaning & Transformation

The raw datasets were prepared using **Power Query** before building the analytical model.

### Key Activities

* Removed unnecessary columns
* Checked and handled missing values
* Corrected data types
* Standardized column names
* Validated date fields
* Checked duplicate records
* Prepared datasets for modeling
* Created required calculated fields

This process ensured that the data was consistent and suitable for reporting.

---

# 🧩 Data Modeling

A **Star Schema** approach was used to structure the Power BI data model.

```text
                    ┌──────────────┐
                    │ Date / Time  │
                    │  Dimension   │
                    └───────┬──────┘
                            │
                            │
┌──────────────┐            ▼            ┌──────────────┐
│   Customer   │──────► Sales Fact ◄─────│   Product    │
│  Dimension   │            │            │  Dimension   │
└──────────────┘            │            └──────────────┘
                            │
                            ▼
                    Geographic Analysis
```

The model allows flexible analysis across:

* Date
* Customer
* Product
* Category
* Sub-Category
* State
* City

---

# 🧮 DAX & KPI Calculations

DAX was used to create business metrics and calculated measures.

### Key KPIs

```text
💰 Total Sales
📈 Total Profit
🛒 Total Orders
📊 Profit Margin
📦 Quantity Sold
```

### Example Business Metrics

```text
Total Sales
Total Profit
Total Orders
Profit Margin %
Average Order Value
```

These KPIs provide a high-level view of the overall business performance.

---

# 📊 Dashboard Design

The Power BI dashboard was designed using multiple interactive visualizations.

### Visualizations Used

* KPI Cards
* Bar Charts
* Line Charts
* Donut Charts
* Tables
* Slicers
* Geographic Analysis
* Category Analysis
* Trend Analysis

### Interactive Features

Users can filter and analyze the data based on different dimensions such as:

```text
📅 Time
🌍 State
🏙️ City
📦 Category
🏷️ Sub-Category
```

---

# 📈 Key Business Insights

## 🥇 1. Clothing is the Top-Performing Category

**Clothing generated approximately ₹488K in profit**, representing around **60% of the total profit**.

This indicates that Clothing is the strongest contributor to overall profitability.

### Recommendation

* Increase inventory for high-performing Clothing products.
* Expand successful Clothing product lines.
* Increase targeted marketing campaigns.

---

## 🌍 2. Uttar Pradesh & Punjab Are Strong Markets

**Uttar Pradesh and Punjab** emerged as strong-performing states.

At the city level:

**Delhi and Chandigarh** showed strong performance.

### Recommendation

* Strengthen marketing activities in high-performing regions.
* Maintain sufficient inventory in these markets.
* Identify successful customer and product patterns for expansion.

---

## 📅 3. January, March & November Show Strong Profitability

The analysis identified:

```text
January
March
November
```

as key months contributing strongly to profit.

### Recommendation

Plan promotional campaigns and inventory strategies around these high-performing periods.

---

## ⚠️ 4. Electronics & Furniture Need Attention

Compared with Clothing, **Electronics and Furniture** show lower profitability.

### Recommendation

* Analyze low-performing products.
* Review pricing and discount strategies.
* Identify products with low margins.
* Improve targeted promotions.
* Optimize inventory planning.

---

# 📸 Dashboard

## 📊 Dashboard — Sales Overview

![Online Sales Dashboard 1](https://github.com/user-attachments/assets/0a2f1cd5-e549-4c5d-b0ba-0e3555153b2f)

---

## 📈 Dashboard — Sales & Profit Analysis

![Online Sales Dashboard 2](https://github.com/user-attachments/assets/cfebe9c7-5824-496e-8cac-82322c26a8d9)

---

## 🌍 Dashboard — Geographic & Product Analysis

![Online Sales Dashboard 3](https://github.com/user-attachments/assets/af784b2b-ea35-43e8-8c30-010cbeba65d7)

---

# 🧰 Technology Stack

| Technology             | Purpose                                 |
| ---------------------- | --------------------------------------- |
| 📊 **Power BI**        | Dashboard development & visualization   |
| 🧹 **Power Query**     | Data cleaning & transformation          |
| 🧮 **DAX**             | KPI & business calculations             |
| 🗄️ **SQL**            | Data analysis & querying                |
| 📗 **Microsoft Excel** | Dataset preparation & analysis          |
| 🌳 **Git/GitHub**      | Version control & project documentation |

---

# 🧠 Skills Demonstrated

```text
✅ Business Intelligence
✅ Power BI
✅ Power Query
✅ DAX
✅ Data Cleaning
✅ Data Transformation
✅ Data Modeling
✅ Star Schema
✅ KPI Development
✅ Sales Analysis
✅ Profit Analysis
✅ Time-Series Analysis
✅ Geographic Analysis
✅ Product Analysis
✅ Interactive Dashboard Development
✅ Business Insights
✅ Data Visualization
```

---

# 🚀 Key Features

* ✔️ Interactive Power BI dashboard
* ✔️ Sales & profit KPI tracking
* ✔️ Profit margin analysis
* ✔️ Product category analysis
* ✔️ State-level analysis
* ✔️ City-level analysis
* ✔️ Monthly sales/profit trends
* ✔️ Interactive slicers
* ✔️ Star schema data model
* ✔️ DAX-based KPI calculations
* ✔️ Business recommendations
* ✔️ Executive-friendly visualizations

---

# 🎯 Business Recommendations

Based on the analysis:

### 1. 📦 Increase Clothing Investment

Clothing is the largest contributor to profitability, so inventory and marketing should focus on high-performing products.

### 2. 🌍 Expand Strong Regional Markets

Uttar Pradesh and Punjab should receive additional marketing and sales attention.

### 3. 📅 Leverage Seasonal Trends

Promotional campaigns should be planned around **January, March and November**.

### 4. 🔍 Improve Underperforming Categories

Electronics and Furniture should be analyzed at product and sub-category levels to identify profitability issues.

---

# 📌 Project Outcomes

This project demonstrates how Power BI can transform raw sales transaction data into actionable business intelligence.

The dashboard provides stakeholders with:

```text
Raw Data
   ↓
Clean Data
   ↓
Data Model
   ↓
DAX Measures
   ↓
Interactive Dashboard
   ↓
Business Insights
   ↓
Data-Driven Decisions
```

The final solution acts as a **centralized sales performance dashboard** for monitoring KPIs, identifying profitable categories, understanding regional performance, and analyzing seasonal trends.

---

# 📂 Repository Structure

```text
Data-Analysis-Dashboard/
│
├── README.md
│
├── Orders.csv
│
├── Details.csv
│
├── Online Book Store Dashboard.pbix
│
└── Dashboard Images/
    ├── Online Sales Dashboard-1
    ├── Online Sales Dashboard-2
    └── Online Sales Dashboard-3
```

> Update the filenames above if the actual files in your GitHub repository have different names.

---

# 🔐 Data & Security

This project uses a simulated dataset for demonstration and portfolio purposes.

No confidential business information, credentials, passwords, API keys, or sensitive connection details should be committed to the repository.

```text
❌ Passwords
❌ API Keys
❌ Database Credentials
❌ Access Tokens
❌ Private Connection Strings
```

---

# 📬 Contact

### **Tanveer Kakar**

**Data Analyst | Data Engineer | Power BI | SQL | Python**

Open to **Data Analyst / Power BI / Data Engineer opportunities**.

---

<p align="center">

### 📊 Built with Power BI • Power Query • DAX • SQL • Excel

**Raw Data → Transformation → Data Model → Dashboard → Business Insights**

</p>
