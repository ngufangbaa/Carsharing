# CarSharing Report with SQL Queries 

## 2017 Car-Sharing Demand & Weather Analysis

### Project Overview

This project analyzes car-sharing demand data for 2017 using SQL. The analysis examines demand patterns across time, weekdays, months, seasons, hours, temperature categories, and weather conditions.

The objective is to identify demand patterns and generate actionable insights that can support marketing campaign planning, customer engagement, and operational decision-making.

---

## Database

**Database:** `carsharing`
**Analysis Period:** 2017
**Primary Analysis Tool:** SQL

The dataset contains car-sharing demand observations alongside weather-related variables, including temperature, humidity, windspeed, and weather conditions.

---

## Analysis Questions

The analysis focuses on the following business questions:

1. What was the highest recorded car-sharing demand in 2017?
2. Which weekday recorded the highest and lowest average demand?
3. Which month recorded the highest and lowest average demand?
4. Which season recorded the highest and lowest average demand?
5. What hours of the day experienced the highest and lowest demand?
6. How does demand vary across temperature categories?
7. Which temperature category was most frequently observed?
8. Which weather condition was most frequently observed?
9. What weather patterns were observed during the highest-demand month?
10. What marketing opportunities can be identified from the demand and weather patterns?

---

## Key Findings

### Demand

* The highest recorded demand was **6.46**, occurring on **15 June 2017 at 17:00**.
* **Saturday** recorded the highest average weekday demand at **4.61**.
* **July** recorded the highest monthly average demand at **4.91**.
* **Fall** recorded the highest seasonal average demand at **4.77**.
* Demand was strongest around the **late-afternoon period**, with 17:00 representing the peak hour for the selected Thursday and Saturday analysis.

### Weather

* **Mild** was the most frequently observed temperature category, accounting for **48.64%** of observations.
* **Clear or partly cloudy** was the most frequently observed weather condition, accounting for **67.28%** of observations.
* **Hot** conditions recorded the highest average demand at **4.97**, followed by Mild at **4.13** and Cold at **3.37**.

### Marketing Implications

The findings suggest opportunities to:

* Concentrate campaigns around high-demand late-afternoon periods.
* Prioritize July and other strong seasonal periods for targeted campaigns.
* Test weather-responsive marketing during warmer conditions.
* Use clear-weather periods as opportunities for customer engagement.
* Reduce promotional emphasis during low-demand overnight periods.

---

## Repository Structure

CarSharing Report/
│
├── README.md
├── SQL/
└── Report/

---

## Supporting Analysis Tables

The detailed SQL output tables are stored in the project's Google Drive folder.

These tables provide the underlying results used in the final report.

### Result Tables & Charts
https://docs.google.com/spreadsheets/d/15tEpvJpRut1xnPzOHVSc96I16TxdRfw-g2yY2m0XVEk/edit?usp=drive_link
---

## Final Report

The complete analytical report provides detailed findings, visualizations, interpretation, and marketing recommendations.

https://drive.google.com/file/d/1fFRTVBks-hq9--82rt1oX-3rFBqf8O0G/view?usp=drive_link

---

## SQL Queries https://eu.docworkspace.com/d/sbRadcRMVbXqmE9W_g9238pa34din01qn4t?sa=601.1037

The SQL queries used to perform the analysis are available in the `SQL` folder of this repository.

The queries cover data exploration, demand analysis, time-based analysis, weather analysis, and marketing-focused insights.

---

## Tools Used

* **SQL** - Data exploration and analysis
* **Google Sheets** - Supporting analysis tables
* **GitHub** - SQL code and project documentation

---

## Business Outcome

This analysis provides the marketing team with data-driven insights into when and under which conditions car-sharing demand was strongest in 2017.

The findings can support campaign timing, weather-responsive marketing, customer engagement, and resource planning.
