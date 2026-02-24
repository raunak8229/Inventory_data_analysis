# 📦 Inventory Data Analysis & Optimization Project

## 📌 Project Overview

This project focuses on analyzing and optimizing inventory management using historical sales, inventory, and purchase data. The goal is to identify demand patterns, classify inventory importance, and design optimal ordering and replenishment strategies that reduce costs while maintaining high service levels.

The analysis follows an **end-to-end data analytics workflow**, from data cleaning to actionable business recommendations.

## 🎯 Objectives

* Understand sales and demand behavior

* Identify high-value and slow-moving products

* Classify inventory using ABC Analysis

* Optimize order quantities using EOQ (Economic Order Quantity)

* Determine optimal reorder timing using Reorder Point (ROP) & Safety Stock

* Provide clear, data-driven business recommendations

## 🧰 Tools & Technologies

* **Python**

* **Pandas, NumPy**

* **Matplotlib** (optional for trends)

* **Jupyter Notebook**

##### Note: Visualization dashboards (Power BI/Tableau) were not required for this project, as the focus was on analytical logic and inventory optimization.

## 📂 Dataset Description

The project uses multiple datasets related to inventory operations:

* **Sales Data** – transaction-level sales quantity and revenue

* **Beginning Inventory** – opening stock levels

* **Ending Inventory** – closing stock levels

* **Purchase Price Data** – unit cost and vendor information

* **Invoice Data** – procurement transactions

**The repository focuses on the analysis and methodology. The datasets were excluded due to size constraints, which is standard practice. I can share them separately if needed.**

## 🔄 Project Workflow

### 1️⃣ Data Cleaning

* Standardized column names

* Handled missing and “Unknown” values

* Converted data types for numerical analysis

* Removed duplicate records

* Ensured data consistency across datasets

### 2️⃣ Exploratory Data Analysis (EDA)

* Analyzed sales trends and demand distribution

* Identified fast-moving and slow-moving products

* Examined vendor contribution to sales and cost

* Compared beginning vs ending inventory levels

## Key insight:
A small number of products contribute disproportionately to total sales value (Pareto principle).

### 3️⃣ ABC Analysis

Products were classified based on cumulative sales value:

* **A items**: Top ~70% of sales value

* **B items**: Next ~20%

* **C items**: Remaining ~10%

This classification helps prioritize inventory control and monitoring efforts.

### 4️⃣ EOQ (Economic Order Quantity) Analysis

EOQ was calculated to determine optimal order quantities using:

* Annual demand derived from sales data

* Assumed fixed ordering cost

* Holding cost estimated as a percentage of unit purchase price

## Outcome:

EOQ highlighted opportunities to reduce overstocking and excessive ordering frequency.

### 5️⃣ Reorder Point (ROP) & Safety Stock

* Calculated average daily demand per product

* Assumed constant lead time

* Incorporated demand variability

* Computed safety stock using a 95% service level

* Determined reorder points to prevent stockouts

## 📊 Final Inventory Policy

Each product was assigned:

* ABC category

* EOQ (optimal order quantity)

* Safety stock

* Reorder point

This created a complete inventory control framework aligned with demand intensity and business risk.

## 💡 Key Business Insights

* A-category items require strict monitoring and higher service levels

* Many C-category items contribute little to revenue but tie up capital

* Inventory levels are not always aligned with actual demand

* Vendor concentration presents potential supply risk

## ✅ Recommendations

* Apply strict EOQ and higher safety stock for A-category products

* Use moderate review cycles for B-category products

* Simplify ordering and reduce inventory for C-category products

* Renegotiate pricing and diversify vendors for critical items

## ⚠️ Limitations

* Ordering cost and lead time were assumed due to data limitations

* Demand seasonality was simplified

* Real-world constraints such as minimum order quantities were not included

## 🚀 Future Enhancements

* Incorporate demand forecasting models

* Use actual vendor lead times

* Apply different service levels by ABC category

* Build an executive dashboard for monitoring KPIs

## 🏁 Conclusion


This project demonstrates how data-driven inventory analysis can support smarter procurement decisions, reduce costs, and improve service levels. It showcases practical applications of ABC analysis, EOQ, and reorder point modeling in a real-world business context.

---

## 👤 Author

**Raunak Ansari**

Aspiring Data Analyst | Python | SQL | Power BI | Excel | Statistics

- **LinkedIn**: (https://www.linkedin.com/in/raunakansari797)
- **GMAIL**: (raunaka48@gmail.com)
