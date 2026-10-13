# ⚽ Excel Football Analytics Dashboard (2020 vs. 2023)

An interactive, multi-season **Football Analytics Dashboard** built in Microsoft Excel. This project harmonizes and compares player performance, team metrics, and squad demographics between the **2020** and **2023** football seasons.

---

## 🚀 Project Overview
The goal of this project is to track how team dynamics, goal-scoring, playmaking, and player age shifted across two distinct seasons. Built entirely in Excel, it highlights advanced data handling techniques—such as multi-source data harmonization and `Distinct Count` aggregations—to deliver accurate, noise-free sports analytics.

---

## 📊 Key Features & Functionality

* **Multi-Season Comparison:** Harmonized player datasets from 2020 and 2023 to enable side-by-side performance analysis.
* **Data Integrity via Distinct Count:** Handled multi-record player entries in the 2023 dataset using PivotTable `Distinct Count` aggregations to eliminate double-counting and ensure precise player statistics.
* **Interactive Slicers:** Dynamic filters allowing users to slice and explore data instantly by:
  * Season
  * Team Name
  * Player Position (Defender, Midfielder, Forward, Goalkeeper)
  * Player Nationality
* **Comprehensive Metrics Tracked:**
  * Player counts (Squad depth)
  * Total Goals (`Sum of Goals`)
  * Total Assists (`Sum of Assists`)
  * Average Player Age (`Average of Age`)
* **Visualized Insights (PivotCharts):**
  * Team summary statistics
  * Team-wise total goals and assists by player position (2020 vs. 2023 comparison)
  * Distribution of players by position across teams
  * Comparative analysis of average player age by position

---

## 🛠️ Tools & Technologies Used
* **Microsoft Excel:**
  * **Data Cleaning & Harmonization:** Standardized fields, data types, and naming conventions across disparate datasets.
  * **PivotTables:** Advanced data aggregation, calculation fields, and `Distinct Count` settings.
  * **PivotCharts:** Built dynamic, responsive charts linked directly to analytical models.
  * **Slicers:** Implemented interactive UI filters for easy dashboard navigation.

---

## 📁 Repository Structure
```text
📦 excel-football-analytics-dashboard
 ┣ 📂 data                 # Raw and cleaned 2020 & 2023 datasets
 ┣ 📂 dashboard            # Excel workbook (.xlsx file containing the dashboard)
 ┣ 📂 screenshots          # Dashboard previews and visual breakdowns
 ┗ 📜 README.md            # Project documentation
