# 📊 Sales Ad Hoc Analysis Dashboard (Power BI)

## 📌 Project Overview

This project presents an interactive Power BI dashboard built to analyze revenue and profitability performance across multiple regional markets for a computer hardware business.

The objective was to identify revenue concentration, margin inefficiencies, and customer dependency risks using structured data modeling and DAX measures.

---

## 🗂 Dataset Description

- Multi-city computer hardware sales dataset  
- ₹984.87M total revenue analyzed  
- 2M total quantity sold  
- Time period: 2017–2020  
- Market-level and customer-level performance tracking  

---

## 🛠 Tools & Technologies

- Power BI  
- DAX (SUM, CALCULATE, Profit Margin %)  
- Star Schema Data Modeling  
- Interactive slicers (Year, Month)  
- KPI Cards & Dynamic Visuals  

---

## 📐 Data Model

Implemented a **Star Schema** structure:

- **Fact Table:** Sales  
- **Dimension Tables:** Date, Market, Customer, Product  

This ensured optimized filtering and accurate KPI computation.

---

## 📊 Key KPIs

- **Total Revenue:** ₹984.87M  
- **Total Profit:** ₹24.66M  
- **Total Quantity Sold:** 2M  
- **Overall Profit Margin:** ~2.5%  

---

## 🔎 Key Business Insights

### 1️⃣ Revenue Concentration

- Delhi NCR contributes ₹519.7M (~52.8% of total revenue)
- High dependency on a single market
- Bhubaneswar and Bengaluru contribute <1% revenue

---

### 2️⃣ Margin Imbalance

- Delhi NCR → ~2.3% margin (high revenue, low efficiency)
- Surat → 4.9% margin (strong margin performance)
- Bengaluru → -20.8% margin (loss-making region)

Indicates pricing or cost optimization opportunities.

---

### 3️⃣ Customer Revenue Dependency

- Electricalsara Stores contributes ~42% of total revenue
- Heavy reliance on top customers increases business risk

---

## 📸 Dashboard Visual Outputs

### Overview Page

![Overview](screenshots/overview.png)

---

### Profitability Analysis Page

![Profitability](screenshots/profitability.png)

---

## 📂 Repository Structure

```
Sales-AdHoc-Analysis-PowerBI
│
├── powerbi/
│   └── Sales_AdHoc_Dashboard.pbix
├── screenshots/
│   ├── overview.png
│   └── profitability.png
└── README.md
```

---

## 🚀 Project Outcome

This dashboard demonstrates:

- Strong KPI modeling
- Profitability analysis capability
- Revenue concentration risk identification
- Practical business insight generation
- Structured Power BI dashboard development

---

## 👤 Author

**Enos Mohod**  
Aspiring Data Analyst | Power BI | SQL | Python  
Turning sales data into actionable business insights
