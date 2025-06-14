#Blinkit Real‑Time Sales Dashboard 📊
An interactive Power BI dashboard simulating real-time analytics for Blinkit (an on-demand grocery delivery app), built from scratch following a comprehensive YouTube tutorial. This project demonstrates end-to-end data modeling, visualization, and dashboard deployment.

🚀 Project Overview
  .Purpose: Visualize Blinkit’s sales and performance metrics — total sales, average sales, item count, ratings — with         filters by outlet location, size, and product category.
  
  .Design: Clean, modern dashboard with cards, trendline, donut and bar charts, funnel visuals, and a summary table.
  
  .Interactivity: Dynamic filters allow users to drill down by outlet size (Tier 1–3), location, and item type.
  
  .Technology: Created using Microsoft Power BI Desktop.

🎯 Key Metrics & Visualizations
Cards:

  .Total Sales (~$1.20 M)
  
  .Average Sales (~$141)
  
  .Number of Items (8,523)
  
  .Average Rating (3.9)

.Trend Over Time: Area chart showing outlet sales evolution (e.g., peaks at $205K in 2018).

.Category Analysis:

  .Donut chart: Sales split between Low‑Fat vs Regular items
  
  .Bar chart: Top-performing item categories by sales (e.g., Fruits, Snacks)

.Outlet Breakdown:

  .Donut: Sales by outlet size
  
  .Funnel: Sales distribution across locations (Tier 1–3)

.Performance Table: Outlet type comparison — total sales, item count, avg. sales, avg. rating, item visibility.

🛠️ Features & Functionality
  Slicer Controls: Filter data by Outlet Location, Outlet Size, and Item Type.
  
  Tooltips & Labels: Contextual insights on hover — values display in thousands or millions.
  
  Drill-through Capability: Navigate tile-by-tile for granular views.
  
  Consistent Color Palette: Shades of green and yellow for coherence and clarity.

📂 Data Modeling & Sources
  Data Sources: CSVs or SQL tables (sales, outlets, items).
  
  Data Model: Fact table (Sales) linked to dimension tables (Outlet, Item).
  
  Measures: Implemented using DAX: Total Sales, Avg Sales, Item Count, Avg Rating, etc.
  
  Time Intelligence: Year-based aggregations (2012–2022 trend view).

📺 Tutorial Reference
Built by following the YouTube tutorial:
“Amazing Real Time Power BI Project | Start to End Analysis” 


🧩 How to Set Up Locally
  Install Power BI Desktop (2024 version recommended).
  
  Clone this repo:

  git clone <repo-url>
  cd blinkit‑powerbi
  Open the Power BI file: BlinkitDashboard.pbix.
  
  Optional: Refresh data source or replace with your own CSVs/SQL connection.
  
  Edit visuals, slicers, or create new measures as needed.
  
  Export via Publish to Power BI Service or Export → PDF/PPT.

🛠️ Learning Takeaways
  Building interactive dashboards using Power BI slicers, visuals, and DAX measures
  
  Designing aesthetically appealing and informative BI reports
  
  Data modeling best practices — fact & dimension relationships
  
  Implementing time-series analysis with dynamic filters
  
  Presenting key business metrics in a clean, user-friendly interface

⚙️ Next Steps
  Connect to real-time sources (e.g., Power Automate, stream analytics)
  
  Add drilldowns to outlet-level geography
  
  Integrate advanced visuals (maps, custom themes)
  
  Automate data refresh and set up alerts in Power BI Service

📦 Folder Structure
  
  /
  ├── data/                 ← Sample CSVs or data dump
  ├── BlinkitDashboard.pbix ← Main Power BI file
  ├── LICENSE
  └── README.md             ← This file
