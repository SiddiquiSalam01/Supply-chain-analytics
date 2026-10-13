# 📦 Supply Chain Analytics Dashboard | Tableau

## 📊 Project Overview

The **Supply Chain Analytics Dashboard** is an interactive Tableau project designed to analyze inventory management, supply and demand, shipment performance, delivery delays, and storage costs.

The project helps businesses monitor inventory levels, identify shipment delays, evaluate overstock and understock situations, and improve supply chain efficiency through data-driven insights.

## 🎯 Project Objectives

- Analyze supply and demand across product categories.
- Monitor inventory balances and inventory trends.
- Identify overstock and understock situations.
- Analyze shipment delays and delivery performance.
- Evaluate shipping status by country and shipment mode.
- Track overstock storage costs over time.
- Support better inventory planning and operational decision-making.

## 🛠️ Tools & Technologies

- **Tableau Desktop** – Dashboard development and visualization
- **Calculated Fields** – Custom business logic and KPIs
- **Data Analysis** – Inventory and shipment performance analysis
- **Interactive Dashboards** – Visual exploration and filtering

## 📈 Dashboard Modules

### 1. Inventory Supply & Demand Analysis

This dashboard focuses on understanding inventory availability compared with demand.

Key analyses include:
- Supply vs. Demand by Category
- Monthly Inventory Balance
- Average Inventory Balance by Category
- Supply-to-Demand Ratio
- Overstock and Understock Classification
- Warehouse Inventory Analysis

**Business objective:** Maintain balanced inventory levels, reduce excess stock, and minimize the risk of stock shortages.

### 2. Shipment Performance Analysis

This dashboard evaluates shipment efficiency and delivery delays.

Key analyses include:
- Average Delay Days
- Delayed Order Rate
- Shipment Delay Trend by Month
- Delay Rate by Market
- Delay Rate by Country
- Delay Rate by Shipment Mode
- Shipment Status Analysis

Shipment status is classified into:
- Early
- On-Time
- 1–5 Days Late
- More than 5 Days Late

**Business objective:** Identify shipment delays, understand delivery performance, and improve logistics efficiency.

### 3. Inventory Storage Cost Analysis

This module examines the cost implications of holding excess inventory.

Key analyses include:
- Overstock Storage Cost
- Overstock Storage Cost by Month
- Storage Cost by Category
- Inventory Value
- Overstock Units

**Business objective:** Reduce unnecessary inventory holding costs and improve warehouse utilization.

## 🔍 Key Calculated Fields

The Tableau workbook includes calculated fields for important supply chain metrics.

| Calculated Field | Purpose |
|---|---|
| Actual Shipment Days | Calculates the number of days between order and shipment dates |
| Delay Days | Measures shipment delay against scheduled shipment days |
| Shipment Status | Classifies shipments based on delay days |
| Delayed Item Flag | Identifies delayed items |
| Delayed Order Rate | Calculates the proportion of orders with delays |
| Inventory Balance | Calculates warehouse inventory minus order quantity |
| Average Inventory Balance by Month | Calculates average inventory balance across distinct dates |
| Inventory Value | Calculates inventory quantity multiplied by unit cost |
| Overstock Units | Identifies inventory exceeding demand |
| Overstock Storage Cost | Estimates storage costs associated with excess inventory |
| Supply-to-Demand Ratio | Compares warehouse inventory with order quantity |

## 💡 Business Insights

The dashboard is designed to help identify the following business opportunities:

- **Inventory Optimization:** Identify categories with excess or insufficient inventory.
- **Demand Planning:** Compare inventory availability with order demand.
- **Shipment Efficiency:** Monitor late deliveries and identify recurring delay patterns.
- **Logistics Improvement:** Compare delay rates across countries and shipment modes.
- **Cost Reduction:** Analyze overstock storage costs and inventory value.
- **Operational Planning:** Use monthly trends to support inventory and shipment planning.

*Specific performance conclusions should be added after reviewing the dashboard results and underlying data.*

## 📂 Repository Structure

```text
Supply-Chain-Analytics-Tableau/
│
├── README.md
├── supply chain analytics_tableau.twb
├── Data/
│   └── fulfillment.csv
│
└── Screenshots/
    ├── inventory-supply-demand.png
    ├── shipment-performance.png
    └── storage-cost-analysis.png
```

*The folder structure above is a suggested repository layout. Add the data and screenshots only if you intend to include them in your GitHub repository.*

## 🚀 How to Use This Project

1. Clone or download this repository.
2. Install Tableau Desktop or use a compatible Tableau application.
3. Open the `.twb` workbook file.
4. If prompted, reconnect the data source to `fulfillment.csv`.
5. Explore the Inventory Supply & Demand and Shipment Performance dashboards.
6. Review the calculated fields and visualizations to understand the analysis.

**Note:** The uploaded workbook references a local CSV file path. Include the required data file in the repository or update the Tableau data connection before sharing the project.

## 📌 Project Outcomes

This project demonstrates the use of Tableau to analyze supply chain operations through interactive dashboards, calculated fields, and visual analytics.

It provides a framework for monitoring inventory balance, identifying shipment delays, analyzing excess stock, and evaluating storage costs to support more efficient supply chain management.

## 👨‍💻 Author

**Salam Siddiqui**

Aspiring Data Analyst | Tableau | Power BI | Excel | Data Analytics

---

⭐ If you find this project useful, consider giving the repository a star!
