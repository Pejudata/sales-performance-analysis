# sales-performance-analysis
Coffee sales performance analysis in Excel
# Coffee Sales Performance Dashboard

An interactive, data-driven Excel dashboard designed to track, visualize, and analyze global coffee sales performance across multiple product lines, countries, and customer segments from 2019 to 2022.

## 📊 Dashboard Overview

This project transforms raw transactional data into actionable business insights. It allows stakeholders to monitor sales trends over time, identify high-value markets, isolate top-performing coffee profiles, and recognize loyal customer behaviors.

![Coffee Sales Dashboard](path-to-your-image.png)

## 🔑 Key Insights & Features

*   **Total Sales Over Time:** A dynamic timeline tracking monthly revenue across four primary coffee bean types: **Arabica**, **Excelsa**, **Liberica**, and **Robusta**.
*   **Sales By Country:** A geographic breakdown showing market dominance, with the **United States** leading revenue followed by Ireland and the United Kingdom.
*   **Top 5 Customers:** A hyper-focused bar chart identifying the highest-spending individual clients to support targeted CRM strategies.
*   **Interactive Slicers:** Deep-dive filtering capabilities including:
    *   **Roast Type:** Dark, Light, Medium
    *   **Package Size:** 0.2 kg, 0.5 kg, 1.0 kg, 2.5 kg
    *   **Loyalty Card Status:** Yes / No
*   **Advanced Timeline Filter:** Smooth chronological scrubbing spanning from July 2019 through early 2022.

## 🛠️ Tech Stack & Functions Used

*   **Software:** Microsoft Excel
*   **Data Modeling:** Power Query (for ETL processing and data cleaning)
*   **Formulas Used:** `XLOOKUP`, `INDEX`, `MATCH`, `IF` statements for data synthesis.
*   **Visualization:** Pivot Tables, Pivot Charts, Custom Theme Layouts, and Dynamic Slicers.

## 📁 Repository Structure

```text
├── Data/
│   └── coffee_sales_raw_data.xlsx  # Raw transactional datasets
├── Dashboard/
│   └── Coffee_Sales_Dashboard.xlsx # Final interactive Excel file
├── Images/
│   └── dashboard_preview.jpg       # Screenshot for README
└── README.md                       # Project documentation
```

## 🚀 How to Use the Dashboard

1. Download or clone this repository to your local machine.
2. Open `Coffee_Sales_Dashboard.xlsx` using Microsoft Excel (Excel 2016 or newer recommended for full slicer compatibility).
3. Use the **Timeline Slider** at the top left to filter specific years or months.
4. Click on any combination of **Slicers** (Roast Type, Size, Loyalty Card) to instantly filter all charts simultaneously.
5. To clear filters, click the **Clear Filter** icon ($x$) at the top right of any slicer block.
