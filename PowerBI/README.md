# 📊 Sales Overview Analysis – Power BI

## 🔥 Project Overview
This Power BI project provides a complete Sales Performance Overview for a business operating across **Central, East, South, and West** regions.  
The dashboard offers **dynamic KPI insights**, **year selection**, **metric switching (Sales, Profit, Quantity)**, and **Previous Year (PY) comparison** to support data-driven decision-making.

---

## 🎯 Business Requirements
### ✅ Core KPIs
- Sales  
- Profit  
- Quantity  

### ✅ Functional Requirements
- Select Year (2021–2024)
- Switch metrics dynamically (Sales/Profit/Quantity)
- Show Previous Year (PY) values for comparison
- Monthly sparklines with average line
- YoY comparison table for Sales, Profit & Quantity

### ✅ Regional Requirements
For **each region – Central, East, South, West**:
- Display Sales, Profit, and Quantity based on selected year  
- Dynamic metric selection  
- Display previous year’s performance  
- Monthly sparkline chart with average indicator  

---

## 🌍 Visualization Requirements
### 📍 Sales by State
- **Bubble Map:**  
  Bubble size indicates total sales volume  
- **Sorted Bar Chart:**  
  Sales comparison across states (Ascending/Descending)

### 📐 YoY Comparison Table
Includes the following metrics:
- CY Sales  | PY Sales  | YoY Sales%
- CY Profit | PY Profit | YoY Profit%
- CY Qty    | PY Qty    | YoY Qty%

---

## 🛠 Data Workflow

### 1️⃣ Requirement Gathering & Understanding  
Based on the business document provided (Problem Statement).

### 2️⃣ Data Walkthrough  
Understanding dataset structure & relationships.

### 3️⃣ Data Connection  
Connecting Excel dataset into Power BI.

### 4️⃣ Data Cleaning (Power Query)
- Removing nulls & duplicates  
- Standardizing formats  
- Ensuring quality checks  

### 5️⃣ Data Modeling
- Star Schema  
- Fact Table: Sales Fact  
- Dimension Tables: Region, State, Products, Calendar  

### 6️⃣ DAX Calculations
Key measures:
- **Total Sales**
- **Total Profit**
- **Total Quantity**
- **Previous Year Sales**
- **YoY % Growth**
- **Metric Switch (SelectedValue)**
- **Average Monthly Performance**

### 7️⃣ Dashboard Design
- Custom background (PPT-designed)
- Layout design for 4 regions
- Proper spacing, alignment, and color theme

### 8️⃣ Report Development
- KPI cards
- Sparklines
- Bubble map
- YoY comparison table
- Dynamic slicers

### 9️⃣ Insights Generation
Key insights are derived based on:
- Regional performance  
- Year-over-year growth  
- High & low performing states  
- Month-wise trends  

---

## 📸 Dashboard Preview
![Dashboard](dashboard.png)

---

## 📂 Files Included
| File Name | Description |
|----------|-------------|
| `sales_overview_report.pbix` | Power BI Dashboard |
| `dashboard.png` | Dashboard Screenshot |
| `dataset.xlsx` | Sales Dataset (Excel) |
| `problem_statement.pptx` | Business Requirement Document |
| `README.md` | Project Documentation |

---

## 🧠 Key Learnings
- DAX for dynamic KPIs & metric switching  
- YoY and Previous Year calculations  
- Power Query cleaning & transformations  
- Professional dashboard layouting  
- Using Bubble Map & Sparklines effectively  
- Business insights storytelling  

---

## 🛠 Tools Used
- **Power BI Desktop**  
- **Power Query (ETL)**  
- **DAX**  
- **Excel**  

---

## 👤 Author
**Zishan Alam**  
Aspiring Data Analyst | Power BI | SQL | Excel  
📧 Email: Zishanalam101@gmail.com 
🔗 LinkedIn: 

---

## ⭐ If you like this project, feel free to Star ⭐ the repo!
