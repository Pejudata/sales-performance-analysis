# Coffee Sales Dashboard

An interactive Excel analytics application designed to track, analyze, and visualize global coffee retail performance. This dashboard aggregates transactional data to deliver actionable insights into product demand, regional market share, and high-value customer behavior.

---

## 📈 Executive Summary

The dashboard provides a centralized interface for monitoring revenue performance from 2019 to 2022. By integrating dynamic cross-filtering, stakeholders can isolate product performance by roast category, packaging size, and customer loyalty enrollment.

<img width="1109" height="547" alt="Coffee Sales Dashboard Overview" src="https://github.com/user-attachments/assets/5fcb4b98-a923-4188-958d-2f869c9a7670" />

---

## 🛠 Features & Visual Components

### 🎛 Global Filter Interface (Slicers & Timeline)
* **Dynamic Timeline:** Allows granular filtering by month and year across multiple years.
* **Roast Profile Filter:** Toggle sales views instantly between **Dark**, **Light**, and **Medium** roasts.
* **Packaging Size Filter:** Segment performance metrics by SKU sizes (**0.2 kg**, **0.5 kg**, **1.0 kg**, and **2.5 kg**).
* **Loyalty Segment Filter:** Compare purchase behavior between **Loyalty Card** holders ("Yes") and guest accounts ("No").

### 📊 Performance Analytics
* **Total Sales Over Time (Line Chart):** Monitors monthly revenue trends across four primary coffee bean varieties: **Arabica**, **Excelsa**, **Liberica**, and **Robusta**.
* **Sales By Country (Horizontal Bar Chart):** Compares market performance across core operating regions: **United States**, **Ireland**, and the **United Kingdom**.
* **Top 5 Customers (Horizontal Bar Chart):** Identifies the highest-value individual purchasers ranked by total expenditure to track customer retention.

---

## ⚙ Technical Architecture

* **Platform:** Microsoft Excel
* **Data Layer:** Utilizes dynamic relational lookup models (`XLOOKUP` / `INDEX-MATCH`) to connect transactional order logs with product and customer dimensions.
* **Aggregation Engine:** Powered by background **Pivot Tables** tied directly to the dashboard canvas via localized Slicer Connections.
* **UI Design:** Implements a cohesive dark purple corporate color palette with clean typography and high-contrast charts to maximize readability.

---

## 🚀 Deployment & Usage Instructions

1. **Initialize Data:** Open the workbook and ensure data links are enabled if prompted.
2. **Time-Series Analysis:** Drag the handles on the **Order Date** timeline at the top left to adjust the analytical time horizon.
3. **Drill Down:** Click individual metric buttons on any slicer (e.g., select `2.5 kg` under Size) to filter all charts simultaneously.
4. **Multi-Select:** Hold `Ctrl` while clicking slicer buttons to select multiple specific attributes.
5. **Reset Canvas:** Click the filter clearing icon (red cross) at the top-right corner of any slicer to return to the global view.
