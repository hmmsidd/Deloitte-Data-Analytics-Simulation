# Deloitte Data Analytics Job Simulation

This repository contains the projects completed during the Deloitte Data Analytics Virtual Experience Program on Forage. The simulation involved real-world data tasks for a client named **Daikibo**.

## Project 1: Telemetry Data Analysis (Tableau)
* **Objective:** Analyze machine telemetry data from Daikibo's factories to identify operational downtime.
* **Dataset Used:** `daikibo-telemetry-data.json`
* **What I Did:** 
  * Imported and cleaned the JSON telemetry dataset in Tableau.
  * Created a custom calculated measure called `Unhealthy` to track potential downtime (10 mins per unhealthy message).
  * Built an interactive dashboard combining "Down Time per Factory" and "Down Time per Device Type".
  * Set up interactive filters to allow dynamic root-cause analysis.

---

##  Project 2: Employee Equality Analysis (Excel)
* **Objective:** Classify employee compensation metrics into equity categories to monitor workplace fairness.
* **Dataset Used:** `Task 5 Equality Table.xlsx`
* **What I Did:**
  * Developed a data classification model using complex nested logical functions (`IF`, `AND`, `OR`).
  * Categorized equality scores into three classes: **Fair** (+-10), **Unfair** (<-10 AND >10), and **Highly Discriminative** (<-20 AND >20).
