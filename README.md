<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:0EA5E9,100:22C55E&height=240&section=header&text=Healthcare%20Operations%20%26%20Waitlist%20Dashboard&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Operational%20Analytics%20for%20Patient%20Waitlist%20Monitoring&descAlignY=58&descAlign=50" alt="banner" />
</div>

<div align="center">

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=111827)](#)
[![SQL](https://img.shields.io/badge/SQL-0F172A?style=for-the-badge&logo=postgresql&logoColor=white)](#)
[![Power Query](https://img.shields.io/badge/Power_Query-1E3A8A?style=for-the-badge&logo=microsoft&logoColor=white)](#)
[![Star Schema](https://img.shields.io/badge/Star_Schema-0B1324?style=for-the-badge&logo=databricks&logoColor=white)](#)

</div>

> A healthcare analytics dashboard focused on tracking patient waitlists, operational pressure, and specialty-level trends through structured reporting and clear visualization.

---

## Overview

This project was built to help healthcare stakeholders monitor waitlist volume, compare case types, and identify operational bottlenecks across specialties and time periods.

It combines **data modeling**, **ETL thinking**, and **dashboard design** to turn complex healthcare data into a more usable decision-support tool.

---

## Business Problem

Healthcare operations teams need clear visibility into:
- patient waitlist growth
- long-wait cases
- specialty pressure points
- case-type distribution
- month-over-month operational trends

Without a structured dashboard, these patterns are harder to track and act on.

---

## Solution

This dashboard organizes healthcare waitlist data into a reporting model that supports:
- operational monitoring
- trend analysis
- specialty comparison
- segmented waitlist profiling

---

## Data Architecture

This project uses a **star schema** approach to keep reporting logic organized and scalable.

```text
Source Data → Cleaning / Transformation → Analytical Model → Power BI Dashboard → Operational Insight
```

### Modeling focus
- fact table for waitlist measures
- dimension views for specialty, case type, and date
- simplified analytical structure for dashboard performance

---

## ETL / Preparation

Data was cleaned and transformed to support consistent reporting and easier filtering inside the dashboard.

Key preparation goals:
- standardize categories
- handle reporting fields cleanly
- prepare for time-based trend analysis
- support stakeholder-friendly dashboard views

---

## Dashboard Insights

Examples of the questions this dashboard can answer:
- Which specialties carry the highest waitlist pressure?
- How many patients have been waiting 18+ months?
- How do case types compare over time?
- Where are operational bottlenecks growing?

---

## Suggested Visual Additions

This README will look even stronger with:
- dashboard overview image
- specialty ranking view
- age / time-band segmentation view
- monthly trend view
- data model screenshot

---

## Why This Project Matters

This project demonstrates:
- analytical structuring
- business reporting logic
- ETL thinking
- data modeling awareness
- practical BI communication

---

## Future Improvements

- add more drill-down interactions
- publish a demo walkthrough
- include a data model diagram image
- add KPI summary cards for executive reporting

---

<div align="center">
  Built by Hazem Elerefy • Healthcare Analytics + BI + Data Modeling
</div>
