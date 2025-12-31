# Maji Ndogo: Visualizing the Currents of Change 🌊📊

*Moulding data into visual stories with Power BI*

---

## Table of Contents
- [Project Overview](#project-overview)
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Building the Data Model](#building-the-data-model)
- [National-Level Insights](#national-level-insights)
- [Visualising Water Queues](#visualising-water-queues)
- [Mapping Water Pollution](#mapping-water-pollution)
- [Connecting Crime and Water Access](#connecting-crime-and-water-access)
- [Key Takeaways](#key-takeaways)

---

## Project Overview

This project explores water access, infrastructure challenges, and environmental risks in **Maji Ndogo** through interactive and insightful **Power BI dashboards**.  
The goal is to transform raw data into compelling visual narratives that support better decision-making and highlight areas for intervention.

---

## Introduction

*A picture is worth a thousand words.*

Data visualization allows us not only to extract insights from complex datasets but also to communicate those insights clearly and effectively. In this project, I move beyond a single-table analysis to leverage **Power BI’s data modeling capabilities**, integrating multiple datasets to uncover deeper patterns and relationships.

Through interactive visuals, this project tells the story of water access, queue dynamics, pollution, and public safety across Maji Ndogo.

---

## Data Source

Instead of connecting directly to a SQL database, this project uses a structured **Excel workbook** containing multiple related tables. You can download the file [here](https://github.com/lawaloa/Visual_2/blob/main/Md_water_services_data.xlsx). Using Excel as the data source simplifies ingestion while still enabling robust relational modeling within Power BI.

---

## Building the Data Model

Power BI’s data model forms the backbone of this project.

Key steps include:
- Importing multiple tables from a single Excel workbook
- Defining relationships between entities such as:
  - Water sources
  - Visits
  - Queue Composition
  - Project progress
  - Location
  - Well Pollution
  - Water Source Related Crime
- Ensuring correct cardinality and filter direction to support accurate analysis

This model enables seamless cross-table analysis and more meaningful visualizations.

<details>
<summary>Click to view chart</summary>
  
![Data Model for Maji Ndogo water_services database](https://github.com/lawaloa/Visual_2/blob/main/Data_Model.png?raw=true)

</details>

---

## National-Level Insights

At the national scale, the dashboards provide a **bird’s-eye view** of survey results, including:
- Distribution of water sources
- Access disparities across regions
- High-level performance indicators

These visuals help identify patterns that may not be obvious at the local level.

---

## Visualising Water Queues

Queue-related visuals were recreated to highlight:
- Average waiting times
- High-traffic water points
- Regional differences in queue behavior

These insights reveal operational bottlenecks and areas where infrastructure upgrades could have the greatest impact.

---

## Mapping Water Pollution

A pollution map was developed to visualize:
- Contaminated water sources
- Geographic clustering of pollution incidents
- Overlaps between water access and environmental risk

This spatial analysis supports targeted cleanup and prevention strategies.

---

## Connecting Crime and Water Access

By linking crime data with water infrastructure:
- New insights emerged around safety risks near water points
- Patterns between long queues and crime incidence were explored
- The analysis highlights how water access intersects with broader social challenges

---

## Key Takeaways

- Power BI data modeling enables rich, multi-table analysis without complex database setups
- Visual storytelling enhances understanding and stakeholder communication
- Integrating environmental and social data provides deeper, more actionable insights
- Data-driven approaches can support equitable and sustainable water solutions

---

📌 *This project demonstrates how thoughtful data modeling and visualization can transform raw datasets into meaningful stories that drive impact.*
