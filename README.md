
[Sales Performance Analysis Dashboard.md](https://github.com/user-attachments/files/26976114/Sales.Performance.Analysis.Dashboard.md)
# Sales Performance Analysis Dashboard

## Overview
This project presents a comprehensive **Sales Performance Analysis Dashboard** developed in Power BI to monitor and evaluate business health across global territories. The dashboard provides a high-level summary of critical sales metrics, including total revenue, order volume, freight logistics, and tax obligations. By leveraging advanced time-intelligence and multi-dimensional analysis, this tool offers actionable insights into regional performance, product trends, and seasonal growth patterns, enabling data-driven strategic planning.

## Data Source
The analysis is based on a multi-year sales dataset (2011-2014) encompassing transaction records, product categories, shipping details, and geographical data. The data was structured to support complex time-intelligence calculations and hierarchical reporting.

## Tools Used
This Sales Performance Dashboard and its analytical components were developed using:
*   **Power BI Desktop:** Utilized for data modeling, advanced DAX calculations, and the creation of an interactive, multi-page reporting suite.
*   **Power Query:** Employed for ETL (Extract, Transform, Load) processes to clean, shape, and optimize the dataset for performance.
*   **DAX (Data Analysis Expressions):** Used to build sophisticated measures for time-intelligence (YTD, QTD, SPLY) and growth tracking.

## Key Findings and Analysis Highlights
The dashboard provides a granular breakdown of the organization's sales performance across several key dimensions.

### Overall Sales Metrics
The following table summarizes the high-level Key Performance Indicators (KPIs) and cumulative performance metrics.

| Metric | Total Value | Growth/Context |
| :--- | :--- | :--- |
| **Total Sales** | $33.93M | Peak performance in 2012 |
| **Total Orders** | 1,000+ | High volume in Canada & Northwest |
| **Total Freights** | $915.97K | ~2.7% of total sales value |
| **Total Tax** | $2.93M | ~8.6% of total sales value |
| **YoY Growth (2012)** | +290.51% | Significant expansion period |

### Time Intelligence & Growth Analysis
A detailed look at the temporal performance reveals strong growth trajectories and seasonal peaks.

| Period | Total Sales | SPLY (Same Period Last Year) | YoY Growth % |
| :--- | :--- | :--- | :--- |
| **2011** | $1,998,992 | - | - |
| **2012** | $7,806,342 | $1,998,992 | **+290.51%** |
| **Total (Overall)** | **$33,933,558** | **$25,155,606** | **+34.89%** |

*   **Monthly Trends:** Sales consistently peak in **July** and **October**, indicating strong seasonal demand.
*   **Cumulative Performance:** The **Running Total** reached its maximum of **$33.93M** by the end of the analyzed period, showing steady upward momentum.

### Regional & Product Performance
Analysis of geographical territories and product categories highlights the primary drivers of revenue.

**Top Territories by Orders:**
*   **Canada:** 448 Orders (Leading Region)
*   **Northwest:** 335 Orders
*   **France & UK:** 188 Orders each

**Product Category Distribution:**
*   **Bikes:** 32.93% of total orders (Primary Revenue Driver)
*   **Components:** 27.49% of total orders
*   **Clothing:** 25.64% of total orders
*   **Accessories:** 13.94% of total orders

**Top Selling Products:**
1.  **AWC Logo Cap:** 428 Orders
2.  **Long-Sleeve Logo Jersey, L:** 425 Orders
3.  **Sport-100 Helmet (Blue/Black/Red):** ~1,000+ combined orders

### Shipping & Logistics Analysis
*   **Freight Efficiency:** Total freight costs are heavily concentrated in **Canada ($0.32M)** and the **Northwest ($0.19M)**, correlating directly with order volume.
*   **Tax Impact:** Tax distribution follows sales volume, with the highest tax contributions coming from the most active sales territories.

## Visualizations
The Power BI report is organized into specialized pages for targeted analysis:
1.  **Main/Landing:** High-level visual summary and navigation hub.
2.  **Overview:** KPI cards and distribution charts for Territory and Product analysis.
3.  **Time Analysis:** Monthly sales vs. orders trends with interactive parameters.
4.  **Product & Shipping:** Deep dives into category performance and logistics costs.
5.  **Time Intelligence:** Granular grid view featuring YTD, QTD, and YoY growth calculations.

## How to Use/Explore
To interact with the full dashboard, please open the provided Power BI file (`.pbix`). Users can utilize the interactive slicers (Year, Month, Territory) to dynamically filter the data. The navigation buttons at the bottom of each page allow for seamless transitions between different analytical views.

## Conclusion
This Sales Performance Dashboard provides a robust framework for global sales monitoring. By integrating advanced DAX measures and interactive visualizations, the organization can identify high-growth regions, optimize product inventory based on demand, and manage logistics costs more effectively, ensuring long-term profitability and market expansion.
