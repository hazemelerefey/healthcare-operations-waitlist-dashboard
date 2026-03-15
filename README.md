# Healthcare Operations & Waitlist Dashboard

A healthcare analytics dashboard focused on tracking patient waitlists, operational pressure, and specialty-level trends through structured reporting and clear visualization.

## Overview
This project was built to help healthcare stakeholders monitor waitlist volume, compare case types, and identify operational bottlenecks across specialties and time periods.

It combines data modeling, ETL thinking, and dashboard design to turn complex healthcare data into a more usable decision-support tool.

## Business Problem
Healthcare operations teams need clear visibility into:
- patient waitlist growth
- long-wait cases
- specialty pressure points
- case-type distribution
- month-over-month operational trends

Without a structured dashboard, these patterns are harder to track and act on.

## Solution
This dashboard organizes healthcare waitlist data into a reporting model that supports:
- operational monitoring
- trend analysis
- specialty comparison
- segmented waitlist profiling

## Tech Stack
- Power BI
- SQL
- Power Query
- Star Schema modeling

## Key Features
- Waitlist trend monitoring over time
- Specialty-level analysis
- Case type breakdown (Inpatient, Day Case, Outpatient)
- Age and wait-time band segmentation
- Dashboard-driven operational insight

## Data Architecture
This project uses a **star schema** approach to keep reporting logic organized and scalable.

### Modeling focus
- fact table for waitlist measures
- dimension views for specialty, case type, and date
- simplified analytical structure for dashboard performance

## ETL / Preparation
Data was cleaned and transformed to support consistent reporting and easier filtering inside the dashboard.

Key preparation goals:
- standardize categories
- handle reporting fields cleanly
- prepare for time-based trend analysis
- support stakeholder-friendly dashboard views

## Dashboard Insights
Examples of the questions this dashboard can answer:
- Which specialties carry the highest waitlist pressure?
- How many patients have been waiting 18+ months?
- How do case types compare over time?
- Where are operational bottlenecks growing?

## Screenshots to Include
- dashboard overview
- specialty ranking page
- age / time-band segmentation view
- trend analysis page
- data model view

## Why this project matters
This project shows more than dashboard design. It also demonstrates:
- analytical structuring
- business reporting logic
- ETL thinking
- data modeling awareness
- practical BI communication

## Future Improvements
- add more drill-down interactions
- publish a demo walkthrough
- include data model diagram image
- add KPI summary cards for executive reporting

## Author
Hazem Elerefy
GitHub: https://github.com/hazemelerefey