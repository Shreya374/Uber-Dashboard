# 🚖 Uber Trip Data Analysis

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

> **Analyzing Uber trip data to uncover ride patterns, peak hours, popular routes, and business insights using Power BI and SQL.**

---

## 📌 Project Overview

This project performs an end-to-end analysis of Uber trip data, combining SQL-based data extraction with interactive Power BI dashboards. The goal is to identify key trends in trip behavior — including peak demand times, popular pickup/drop-off zones, trip durations, and revenue patterns — that can help drive data-backed decisions.

---

## 🎯 Objectives

- Analyze trip frequency across different times of day, days of week, and months
- Identify the most popular pickup and drop-off locations
- Understand trip duration and distance distributions
- Uncover revenue and demand trends over time
- Build an interactive dashboard for dynamic exploration

---

## 🗂️ Dataset

| Attribute | Details |
|---|---|
| **Source** | Uber Trip Records (Public / Kaggle) |
| **Format** | CSV / SQLite Database |
| **Key Columns** | Trip ID, Pickup DateTime, Dropoff DateTime, Pickup Location, Dropoff Location, Trip Distance, Fare Amount |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **SQL / SQLite** | Data extraction, filtering, and aggregation |
| **Power BI** | Interactive dashboard and data visualization |
| **Power Query Editor** | Data cleaning and transformation |

---

## 📊 Dashboard Highlights

The Power BI dashboard includes:

- 📅 **Trip trends** — Daily, weekly, and monthly ride volume
- ⏰ **Peak hours heatmap** — Busiest hours across days of the week
- 📍 **Top pickup & drop-off zones** — Most frequently used locations
- 💰 **Revenue analysis** — Fare distribution and average fare over time
- 🗺️ **Geographic map** — Visual trip distribution across the city
- ⏱️ **Trip duration analysis** — Average trip duration by zone and time

---

## 🔍 Key Insights

- 🕔 **Peak demand** occurs on **weekday evenings (5 PM – 8 PM)** and **Friday/Saturday nights**
- 📍 **Downtown and airport zones** account for the highest trip volume
- 💵 **Average fare** increases significantly during peak hours (surge pricing effect)
- 📉 **Trip volume dips** on Sunday mornings and mid-week afternoons
- 🚗 Short trips (< 5 km) make up the majority of all rides

> *Insights may vary based on the specific dataset used.*

---

## 📁 Project Structure

```
Uber_Trip_Data_Analysis/
│
├── data/
│   └── uber_trips.db           # SQLite database
│
├── sql/
│   └── queries.sql             # All SQL queries used for analysis
│
├── dashboard/
│   └── Uber_Analysis.pbix      # Power BI dashboard file
│
├── screenshots/
│   └── dashboard_preview.png   # Dashboard screenshot
│
└── README.md
```

---

## 🚀 How to Run

**SQL Analysis:**
1. Open `uber_trips.db` using any SQLite viewer (e.g., DB Browser for SQLite)
2. Run queries from `sql/queries.sql` to explore the data

**Power BI Dashboard:**
1. Open `Uber_Analysis.pbix` in **Power BI Desktop**
2. Refresh the data source if needed
3. Interact with slicers and visuals to explore insights



---

## 🙋‍♀️ Author

**Shreya Jagtap**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shreya-jagtap)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/shreya-jagtap)


---

## ⭐ If you found this project helpful, please give it a star!
