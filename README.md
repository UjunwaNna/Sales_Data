# Employee Sales Performance Dashboard
This repository contains an end-to-end data analysis project showcasing proficiency in data organization, analytics, and visualization using Microsoft Excel. 
The project evaluates over 500 employee sales records across multiple regions and departments, transforming raw,
unstructured data into an interactive, professional dashboard.
 
**Full Interactive Analysis Spreadsheet:https://1drv.ms/x/c/dbc68fe0ab4d6b41/IQABXmYQCkhcRqgYJNo-QKkHAaIRQw5XuH_iZWwbSKa7_pk?e=IVaA5R**


## Project Overview

The goal of this project is to analyze employee sales performance and generate actionable business insights. 
It demonstrates a complete data workflow—from cleaning and structuring to advanced analysis and visual storytelling.

**Dataset:** 500+ employee sales records across various departments and regions.

**Primary Tool:** Microsoft Excel (Formulas, Conditional Formatting, PivotTables, PivotCharts, and Dashboards).

## Stages of Analysis

**1. Data Cleaning & Preparation**

Raw data often contains formatting inconsistencies, trailing spaces, and mixed data types.

The following techniques and Excel functions were utilized to sanitize the dataset:

**Text & Character Cleaning:** Applied SUBSTITUTE, CLEAN, and VALUE functions to remove unwanted symbols, hidden spaces, and text formatting errors.

**String Extraction:** Used LEFT, RIGHT, and MID functions to extract and correct numerical and text values from mixed data cells.

**Standardization:** Ensured uniform number formatting and verified data accuracy by checking for duplicates and inconsistencies.

## 2. Data Analysis & Transformation

Once cleaned, the data was enhanced with calculated fields and logical rules to segment performance:

**Aggregation**: Calculated total sales per employee by summing quarterly figures (Q1–Q4

**Performance Categorization:** Implemented nested IF statements to group employees into distinct performance tiers:

**High Performer:** >= $200K

**Mid Performer:** $180K - $199K

**Low Performer:** < $180K

**Ranking:** Integrated rating and ranking systems to easily identify top contributors.

## 3. Conditional Formatting & Visual Cues

**Highlighted the Top 10 Highest Producers in red for instant recognition (Employee Total Sales).**

**Applied three-color scales (green–yellow–red) to visualize performance ratings across tiers.**

**Used color-coded sales tables to enhance overall readability.**

## 4. Data Visualization & Dashboard Design

Designed a dynamic, interactive Excel Dashboard featuring PivotTables and PivotCharts to summarize key metrics:

**KPI Cards:** Display total sales, department count, and regional performance.

**Sales Trends:** Breakdown of total sales overview and quarterly trends by region.

**Rankings & Distributions:** Top 10 employees by total sales, sales by department, and sales by region.

**Interactivity:** Implemented slicers and drop-down data validation lists enabling users to instantly select an employee's 
name to view their department, region, and total sales.

## Summary of Tools & Techniques

**Data Cleaning Functions:** SUBSTITUTE, VALUE, CLEAN, MID, LEFT, RIGHT**

**Logical & Analytical Functions:** IF, SUM, RANK

**Visualization Features:** PivotTables, PivotCharts, Custom Color Scales, and KPI Cards

## Repository Structure
**Raw Data:** Original, unmodified employee sales dataset.

**Cleaned Data:** Pre-processed and standardized dataset ready for analysis.

**Pivot Tables:** Summarized tables for dynamic data exploration.

**Dashboard:** Fully interactive Excel workbook containing the visual dashboard and charts.
