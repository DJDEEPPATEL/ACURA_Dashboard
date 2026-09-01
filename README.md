# Acura 2026 Sales Dashboard (Power BI)

An interactive Power BI dashboard tracking Acura vehicle sales across Canada from January to August 2026. Built end-to-end on synthetic (AI-generated) sales data to simulate a realistic dealership analytics environment.

## Overview

The dashboard covers six Acura models — ADX, Integra, MDX, NSX, RDX, TLX, and ZDX — each on its own tab, with consistent KPIs and visuals for easy comparison across the lineup.

Each model page includes:
- **Total Sales & Total Units Sold** — headline KPIs
- **Top 3 Dealerships in Canada** — leaderboard by units sold
- **Number of Cars Sold by Province** — bar chart breakdown
- **Total Upgrades Sold with New Car** — donut chart (trim/package mix)
- **Monthly Sales Performance and Trend** — Jan–Aug 2026 revenue trend

## Key Feature: Dynamic Color Sync

The standout feature of this build is the **Exterior Colour selector** — when a user picks a car color from the dropdown, every visual on the page (KPI cards, bar chart, donut chart, trend chart) re-themes to match that color in real time. Instead of a static report, the whole page visually reflects the selected trim, tying the data experience directly to the product being analyzed.

## Tech Stack

- **Power BI Desktop** — data modeling, DAX measures, report design
- **Power Query** — data transformation and cleanup
- Data model built around a central `Sales_Data_Master` table with dimensions for dealership, province, model, trim, exterior color, and upgrades

(https://github.com/DJDEEPPATEL/ACURA_Dashboard/blob/main/Home.png)
![Summary Page](https://github.com/DJDEEPPATEL/Healthcare-Dashboard/blob/main/Home_Page.png)
See `/screenshots` for full-page views of the dashboards.

## Notes

All sales data in this project is synthetically generated for demonstration and portfolio purposes and does not reflect real Acura sales figures.

## Author

Built by [Your Name] as a data visualization / Power BI portfolio project.
