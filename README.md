# 📦 Supply Chain Analytics — Just In Time

A data analytics project focused on uncovering supply chain inefficiencies, optimizing inventory management, and analyzing shipment performance for **Just In Time**, a retail company. This project was completed as part of a **DataCamp competition**.

---

## 📌 Project Overview

As the lead data analyst for Just In Time, the goal of this project is to:

- Identify and resolve **shipment delays** across different regions and shipment modes
- Analyze **inventory storage costs** by product and department
- Evaluate **business performance** through profitability metrics
- Provide actionable insights to business stakeholders via an interactive **Power BI dashboard**

---

## 🗂️ Repository Structure

```
Supply_Chain_analytics/
│
├── Orders_and_shipments.csv     # Raw order and shipment transaction data
├── Inventory.csv                # Warehouse inventory levels and unit costs
├── Fulfillment.csv              # Order fulfillment time per product
├── Supply_Chain_Analytics.ipynb # Data cleaning & preparation notebook (Python)
├── PowerBI_Dashboard.png        # Dashboard screenshot
└── README.md
```

---

## 📊 Dashboard Preview

![Power BI Dashboard](<Supply chain analytics/PowerBI_Dashboard.png>)

The Power BI dashboard includes 5 views:
- **Business Performance** — Most profitable goods, total profit trend, profit by department
- **Inventory Management** — Inventory storage costs by product and department
- **Shipment Investigation** — Shipment modes and delivery performance
- **Shipment Delay Details** — Root cause analysis of late deliveries
- **Order Fulfillment Days** — Warehouse fulfillment time analysis

> 📌 Most Profitable Month: **August 2016** — Profit of **$134,801**

---

## 🧹 Data Preparation (Python)

The notebook `Supply_Chain_Analytics.ipynb` covers:

- **Data loading** from 3 source CSVs: orders & shipments, inventory, fulfillment
- **Exploratory Data Analysis (EDA)** — shape, dtypes, missing values, duplicates
- **Data cleaning** — handling nulls, removing anomalies, fixing data types
- **Feature engineering** — computing `Order Processing Time`, converting date columns to `datetime`
- **Exporting** cleaned CSVs for further visualization in Power BI / Tableau

### Datasets Summary

| Dataset | Rows | Key Columns |
|---|---|---|
| Orders & Shipments | 30,871 | Order ID, Product, Customer, Shipment Mode, Gross Sales, Profit |
| Inventory | 4,200 | Product Name, Year Month, Warehouse Inventory, Inventory Cost Per Unit |
| Fulfillment | 118 | Product Name, Warehouse Order Fulfillment (days) |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy) | Data cleaning & preparation |
| Google Colab | Development environment |
| Power BI | Dashboard & visualization |
| GitHub | Version control |

---

## 🔍 Key Metrics Analyzed

- **Profit Margin** by product and department
- **Inventory Storage Cost** over time
- **Shipment Delay** (actual vs. scheduled delivery days)
- **Inventory-to-Sales Delta** to detect overstock/understock
- **Order Fulfillment Time** per product

---

## 💡 Key Findings

- **Perfect Fitness Perfect Rip Deck** has the highest inventory storage cost
- **Apparel** and **Fan Shop** departments consistently drive the most profit
- Profit peaked in **August 2016** and saw a significant drop heading into **2018**
- Products like **Nike Men's Dri-FIT** and **O'Brien Men's** rank highest in profit margin

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/ShivamPatidar3/Supply_Chain-_analytics.git
   ```
2. Open `Supply_Chain_Analytics.ipynb` in Google Colab or Jupyter Notebook
3. Upload the CSV files and run all cells
4. Use the exported CSVs in Power BI to explore the dashboard

---

## 🙋 About

This project was built as part of a **DataCamp competition** to demonstrate real-world data analytics skills including data wrangling, exploratory analysis, and business intelligence dashboarding.

> *As an aspiring data analyst, I strive to use effective data processing and advanced analytics to generate meaningful conclusions that support decision-making.*

---

## 📬 Connect

**Shivam Patidar** — [GitHub](https://github.com/ShivamPatidar3)
