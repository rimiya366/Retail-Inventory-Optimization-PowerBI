# Retail Supply Chain & Inventory Optimization Suite (Power BI)

An interactive, three-tier Power BI report designed to optimize retail inventory, track sales performance, and reduce warehouse carrying costs. This project bridges the gap between high-level executive KPIs, supply chain forecasting, and daily storefront operations.

---

## 📌 Project Overview & Key Metrics
This project analyzes a retail dataset tracking **$98.73M in revenue** and over **2M units sold**. 

* **The Problem:** While the business maintained a perfect 0% stockout rate, **65.16% of the total inventory was trapped as Overstocked Surplus** (3M units). This represents significant capital frozen in excess warehouse storage.
* **The Solution:** A three-page analytical report that isolates forecasting errors and provides store managers with daily, actionable checklists to balance inventory.

---

## 📊 The Three-Tier Dashboard Architecture

### Page 1: Executive Inventory Overview
Designed for company leadership to monitor high-level business health and category performance at a glance.
* **Key Visuals:** High-level KPI cards, Top Categories by Revenue (Horizontal Bar Chart), Overall Inventory Status (Doughnut Chart), and Units Sold vs. Demand Forecast (Combo Chart).
* **Core Insight:** Reveals that our ordering software over-predicted summer demand, causing the 65% overstock surplus.

*Insert Page 1 Screenshot Here*
![Executive Dashboard](images/Page1.png)

---

### Page 2: Demand Forecasting & Supply Chain Optimization
Designed for supply chain planners to audit and improve our predictive ordering models.
* **Key Visuals:** Impact of Promotion on Sales by Weather (Grouped Bar Chart), Monthly Sales vs. Forecast Trends, and Regional Performance Grid (Cross-Tab Matrix).
* **Core Insight:** Shows that while weather does not impact sales volumes, holiday promotions consistently lift sales. The forecasting model remains highly stable with a uniform **93.89% Forecast Accuracy Rate** across all geographic regions (East, North, South, West).

*Insert Page 2 Screenshot Here*
![Planning Dashboard](images/Page2.png)

---

### Page 3: Store & Stock Optimization: Operational Action List
A prescriptive, daily execution tool designed for individual store managers.
* **Key Visuals:** Price Comparison vs. Competitors (Dual Bar Chart) and The Store Manager's Live Action Grid (Interactive Task Table).
* **Core Insight:** By selecting a specific **Store ID**, the manager receives a dynamic daily to-do list with color-coded status badges:
  * 🟢 **Optimal Stock:** Balanced levels; no action needed.
  * 🟡 **Understocked Risk:** Low stock; request immediate replenishment.
  * 🔴 **Overstocked Surplus:** Excess stock; stop ordering and use the price comparison tool to run safe local discount campaigns.

*Insert Page 3 Screenshot Here*
![Operations Dashboard](images/Page3.png)

---

## 🛠️ Key Design & Layout Choices
* **Clean Scannability:** Designed with a cohesive color palette and clear boundaries to ensure users can find critical metrics in under 3 seconds without "data clutter."
* **Dynamic Slicers:** Right-side button slicers allow users to instantly filter the entire report suite by Region, Category, Date, or Store ID.
* **Actionable Layout:** Rather than just showing static graphs, the system translates data directly into visual, color-coded daily operational tasks for staff.

---

## 📁 Repository Structure
* `/images` - Contains dashboard screenshots used in this README.
* `Retail_Inventory_Optimization.pbix` - The core Power BI project file (includes data model and visual layers).
* `README.md` - Project documentation.
