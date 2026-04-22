# 👕 Men’s Clothing Sales & Profit Analysis Dashboard

## 📌 Project Overview
This project analyzes men’s clothing sales performance using data stored in **Azure SQL Database** and visualized through **Power BI**.  
It focuses on brand-wise performance, pricing strategies, discount impact, and profitability insights.

---

## 🛠️ Tools & Technologies
- Microsoft Azure SQL Database
- SQL Server
- Power BI
- DAX (Data Analysis Expressions)

---

## 🔄 Steps Followed

- **Step 1: Azure Setup**
  - Created Azure account (Free Trial)
  - Set up Azure SQL Database
  - Uploaded dataset into Azure SQL Database

- **Step 2: Data Processing in SQL Server**
  - Connected Azure SQL Database to SQL Server
  - Performed data cleaning and transformations
  - Structured data for analysis

- **Step 3: Connecting Power BI**
  - Connected Power BI to Azure SQL Database
  - Imported processed data into Power BI

- **Step 4: Data Modeling**
  - Organized dataset inside Power BI
  - Created calculated columns:
    - Profit %
    - Discount %
  - Built measures using DAX

- **Step 5: Data Visualization**
  - Created dashboards including:
    - Top 5 brands by discount %
    - Top 5 brands by profit %
    - Brand-wise variety distribution
    - Average sales price analysis
    - Profit % distribution

- **Step 6: Dashboard Design**
  - Designed clean and modern UI
  - Used consistent color theme
  - Focused on readability and storytelling

- **Step 7: Deployment**
  - Published report to Power BI Service
  - Created workspace
  - Enabled sharing

---

## 📊 Snapshot of Dashboard

![Landing](https://raw.githubusercontent.com/komalchoudhary1021-cmyk/Mens-Clothing-Performance-Analysis-Project-4/main/Men1.png)

![Dashboard](https://raw.githubusercontent.com/komalchoudhary1021-cmyk/Mens-Clothing-Performance-Analysis-Project-4/main/M2.png)

![Analysis](https://raw.githubusercontent.com/komalchoudhary1021-cmyk/Mens-Clothing-Performance-Analysis-Project-4/main/Men3.png)

---

## 📈 Key Insights

- High discounts do not always result in higher profits  
- Certain brands dominate both in variety and revenue  
- Profit % remains relatively consistent across brands  
- Pricing strategy significantly impacts overall performance  

---

## 🧾 DAX Calculations

- **Profit %**
  
Profit % = DIVIDE([Sale Price] - [Cost Price], [Cost Price])


- **Average Discount %**

Average Discount % = AVERAGE([Discount %])


- **Average Sales Price**

Average Sales Price = AVERAGE([Sale Price])


---

## 📌 Conclusion

This dashboard helps businesses:
- Analyze brand performance  
- Optimize pricing strategies  
- Improve discount planning  
- Enhance profitability decisions  
