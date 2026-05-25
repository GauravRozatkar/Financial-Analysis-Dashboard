# Financial-Analysis-Dashboard
Power BI Analytics Case Study & Dashboard
An end-to-end Power BI business intelligence project implementing advanced data modeling, DAX calculations, interactive bookmarking, and dynamic dashboards based on real-world business scenarios.

📊 Project Overview
This repository contains the comprehensive solution to a multi-part Power BI analytics assignment. The project spans business metrics analysis, dynamic data integration from web sources, complex data modeling, and the creation of an interactive corporate financial dashboard.

All solutions are packed cleanly into a single unified .pbix workbook file.

🛠️ Case Study Solutions & Features
1. Architectural & Platform Analysis (Q1)
Comprehensive breakdown of the Power BI ecosystem components (Power BI Desktop, Power BI Service, and Power BI Mobile) and how they facilitate the enterprise BI lifecycle.

2. Advanced DAX & Time-Intelligence (Q2)
Metrics Tracked: Current Year Sales vs. Last Year Sales and YoY Growth %.

Implementation: Built dynamic Time-Intelligence measures using DAX to compare comparative sales performance across continuous date dimensions using the Superstore dataset.

3. Dynamic Web Scraping & Data Modeling (Q3)
ETL Pipeline: Extracted real-time worldwide box office metrics dynamically from Box Office Mojo.

Power Query Transformation: Appended and consolidated a 3-year historical dataset, generated an optimized central master table, and utilized "Enable Load" parameters to streamline performance by only passing final models to the Power BI Desktop engine.

4. Advanced Visualizations & Hierarchies (Q4, Q5, Q7)
Waterfall Charts: Implemented Category-wise Yearly Analysis to pinpoint specific operational growth drivers and leakages.

Geographic Hierarchies: Engineered a custom Location hierarchy (Country ➔ State ➔ Region ➔ City ➔ Postal Code) to deliver intuitive, multi-level geographic sales analysis.

Drill-Through Actions: Created a regional Profit Donut Chart equipped with targeted page-level drill-through mechanisms focused on the West Region.

5. Interactive UI/UX Elements (Q6, Q9)
Bookmark Navigation: Programmed custom canvas bookmarks allowing users to fluidly toggle a single Clustered Column Chart across Year, Quarter, and Month granularities for Sales, COGS, and Profit.

Dashboard Experience: Built a unified, highly polished Finance Dashboard integrated with KPI cards, navigation buttons, external web hyperlinks, and centralized slice controls.

6. Conditional Formatting (Q8)
Implemented custom, condition-based formatting rules on product sub-categories to drastically improve dashboard scanability:

Sales: Dynamic background gradients shifting from Red (Lowest) to Green (Highest).

Profit: KPI indicator icons (🔴 down arrows for negative profit, 🟢 up arrows for positive profit).

Quantity: Inline native data bars representing volume distribution.

Discount: High-contrast text alerting for margin protection (Red font for lowest discounts, Green for highest).

🖥️ Dashboard Preview
Figure: Final Financial Dashboard UI showcasing automated KPI tracking, trend breakdowns, and modular filtering layouts.
