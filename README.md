## COVID-19 SQL Analysis (Australia Dataset)

This repository contains SQL queries for analyzing COVID-19 data stored in a table named **`Australia`**.  
The dataset includes columns for **Confirmed**, **Deaths**, **Recovered**, and **Observation_Date**, along with **Province_State** information.


## Project Overview
The queries in this project demonstrate how to:
- Create and use a dedicated database (`covid`).
- Calculate overall totals of confirmed cases, deaths, and recoveries.
- Perform **province-level analysis**:
  - Aggregate totals per province.
  - Identify provinces with the highest confirmed cases, deaths, and recoveries.
- Perform **time-based analysis**:
  - Extract year and month from `Observation_Date`.
  - Summarize totals by year and month.
- Compute **recovery rates**:
  - Recovery rate per province.
  - Recovery rate per month.
- Rank and order results to highlight provinces or months with the highest values.

