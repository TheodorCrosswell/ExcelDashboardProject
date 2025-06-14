# Coffee Sales Dashboard - An Advanced Excel Project

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

This project is a fully interactive and dynamic sales dashboard built entirely in Microsoft Excel. It analyzes coffee sales data, providing key insights into performance over time, by country, and by customer. The dashboard is designed to be a powerful, at-a-glance tool for business intelligence, demonstrating advanced data modeling, analysis, and visualization techniques.

## Dashboard Showcase

The dashboard is designed to be clean, intuitive, and responsive. Below are two views: one filtered for a specific date range and another showing all historical data.
![Dashboard](https://github.com/TheodorCrosswell/ExcelDashboardProject/blob/84de9be465587e3930fe6f9cd5938ca98ce7f381/complete_project/Screenshot%202025-06-10%20145703.png)

---

## Key Features & Skills Demonstrated

This project showcases proficiency in a range of intermediate to advanced Excel features:

*   **PivotTables & PivotCharts:** All visualizations are driven by PivotTables, ensuring that the data is aggregated efficiently and accurately. This allows for complex analysis, such as:
    *   Sales trends broken down by product category (`Arabica`, `Excelsa`, `Liberica`).
    *   Sales performance aggregated by country.
    *   Dynamic ranking of top customers.

*   **Interactive Controls (Slicers & Timelines):** The dashboard is highly interactive, allowing users to filter the entire report with a single click.
    *   **Timeline Slicer:** Provides an intuitive way to filter data by `Order Date`, allowing users to drill down into specific months or years.
    *   **Slicers:** User-friendly buttons for filtering by `Roast Type`, `Size`, and `Loyalty Card` status. All slicers are interconnected and control every chart on the dashboard simultaneously.

*   **Advanced Charting & Visualization:**
    *   **Combination Charts:** The "Total Sales Over Time" line chart effectively displays trends for multiple categories at once.
    *   **Bar Charts:** Clean and clear bar charts are used for comparing categorical data like sales by country and customer.

*   **Dashboard Design & UI/UX:**
    *   **Professional Layout:** A clean, grid-based layout using shapes and text boxes creates a modern, app-like interface.
    *   **Consistent Formatting:** A deliberate color scheme and consistent font usage make the dashboard easy to read and professionally appealing.
    *   **Clutter-Free View:** Gridlines, headings, and the formula bar are hidden on the dashboard sheet to create an immersive, report-only experience.

---

## Technical Breakdown

1.  **Data Source:** The analysis is based on two relational tables (a sales transaction table and a customer dimension table).
2.  **Presentation Layer:** The main `Dashboard` sheet pulls in the **PivotCharts** from the analysis sheet. **Slicers** and a **Timeline** are connected to the underlying PivotTables to provide interactivity. Shapes, text boxes, and careful formatting are used to build the final polished interface.

This project effectively transforms raw tabular data into a powerful, interactive, and insightful business intelligence tool using only the native capabilities of Microsoft Excel.
