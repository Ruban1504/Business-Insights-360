Business Insights 360°
======
![Chat Preview](https://imgur.com/WKzOGoD.png)


---


## Overview
This repository contains a project focused on improving the sales of a pizza company
through **Data Analytics** techniques. 
**Business Insights 360** is a comprehensive data analysis project focused on uncovering actionable insights and business trends from pizza sales data. Leveraging tools like Excel, Power BI, and SQL Server, the project analyzed over **50,000 rows** of sales data to identify patterns and drive strategic decision-making.



---

## Problem Statement
The challenge in the project is discover
1. Financial Trends of the shop.
2. Foods that are performing well and not well.
3. Need to view data at a more granular level.

---
## Dataset
The **sales dataset** is a simulated dataset containing:
- **45000+ sales records**.
- Information about id, order_date, order_time, pizza_orderd etc,.

---
## Project Workflow

1. **Problem Identification**:
   - Figured out the meausres needed to calculate in order to address the problems.
   - Listed out the KPI measures and related charts.

2. **Data Preprocessing**:
   - Loaded the data in Excel and Cleaned raw data.
   - Standardized the colum names, and performed cleaning operation.
   - Got a rough insight about the dataset.
   
3. **Power BI**:
   - Calculated the measures needed for the project.
   - Visualized all the measures and charts through cards and charts.
   - Developed  **two** interactive dashboards 

4. **Cross Validation**:
   - Imported the data in **MySQL**, and calculated all the values performed in Power BI      to cross check the results.
   
5. **Documentation**:
   - Documented all the SQL Queries in Word and uploaded it in GitHUB.

Description
Below is the detailed field of each sub-dataset.
## Pizza Sales 
| Data field                 | Description                                  | Unit/format  |
|----------------------------|----------------------------------------------|--------------|
| pizza_id                | unique id to each pizza             | int           |
| order_id         | id for each order           | int        |
| pizza_name_id            | unique id for each pizza         | String         |
| quantity                   | quantity ordered for each order                     | int        |
| order_date                  | date of order                                         | Date       |
| order_time               | time of order                              | DateTime      |
| unit_price                | unit price of each pizza               | Decimal          |
| total_price                   | total price                               | Decimal  |
| pizza_size                 | Size of the pizza                            | Categorical           |
| pizza_category                | sub category of pizza    | Categorical        |
| pizza_ingredient          | items used to prepare the pizza | String       |
| pizza_name         | name of the pizza |String        |

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Ruban1504/Business-Insights-360.git
