##  Product Group Performance Report
---
<img width="1112" height="726" alt="image" src="https://github.com/user-attachments/assets/13515ac0-3064-4c38-9445-5d52f8b024b7" />

---

### Excel Sales Data Analysis Using Pivot Tables

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Data Preparation Task](#data-preparation-task)
- [Analysis Tasks](#analysis-tasks)
  - [Top 5 Best-Selling Product Groups for Each Year](#top-5-best-selling-product-groups-for-each-year)
  - [Top 5 Best-Selling Product Groups (2011–2014)](#top-5-best-selling-product-groups-20112014)
  - [Best-Selling Outlet / Store (2011–2014)](#best-selling-outlet--store-20112014)
  - [Top 10 Producers (2011–2014)](#top-10-producers-20112014)
- [Slicers Usage](#slicers-usage)
- [Dashboard](#dashboard)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)

---

## Project Overview

This project analyses sales data using Microsoft Excel Pivot Tables to identify performance trends, best-selling product groups, and top-performing producers. The objective is to transform raw data into actionable business insights.

---

## Dataset Description

The dataset contains transactional sales data with the following fields:

| Field | Description |
|------|-------------|
| **Year** | Sales year |
| **Type** | Sales category / classification |
| **Product group** | Product category |
| **Producer** | Manufacturer / supplier |
| **Code** | Product identifier |
| **Volume** | Quantity sold |
| **Cost per unit** | Unit price / cost |

---

## Data Preparation Task

Before analysis, the dataset undergoes basic cleaning and preparation:

- Checked for missing or blank values
- Ensured consistent data formatting
- Verified numeric fields (Volume, Cost per unit)
- Removed duplicate records
- Standardized text entries (Product groups, Producers)

These steps ensure accuracy and reliability of the Pivot Table outputs.

---

## Analysis Tasks

### Top 5 Best-Selling Product Groups for Each Year

**Method:**

- Inserted Pivot Table
- Rows → Product group
- Columns → Year
- Values → Sum of Volume
- Sorted Volume in descending order
- Applied Top 5 filter per year

**Purpose:**  
To identify yearly product performance trends.

---
<img width="492" height="270" alt="image" src="https://github.com/user-attachments/assets/c0a228c3-783e-4c23-879e-6ee9e150dd4f" />

---

### Top 5 Best-Selling Product Groups (2011–2014)

**Method:**

- Filtered Year → 2011–2014
- Rows → Product group
- Values → Sum of Volume
- Applied Top 5 filter

**Purpose:**  
To determine overall high-performing categories across the selected period.

---
<img width="698" height="671" alt="image" src="https://github.com/user-attachments/assets/5a239b81-a594-4792-830e-1ef368f92ccb" />

---

### Best-Selling Outlet / Store (2011–2014)

**Method:**

- Filtered Year → 2011–2014
- Rows → Outlet / Store
- Values → Sum of Volume
- Sorted descending

**Purpose:**  
To identify the strongest sales channel.

---
<img width="452" height="242" alt="image" src="https://github.com/user-attachments/assets/0c05cb82-14d5-4457-8359-25b739e2919b" />

---

### Top 10 Producers (2011–2014)

**Method:**

- Filtered Year → 2011–2014
- Rows → Producer
- Values → Sum of Volume
- Applied Top 10 filter

**Purpose:**  
To evaluate supplier performance.

---
<img width="413" height="421" alt="image" src="https://github.com/user-attachments/assets/09022886-0637-4a2f-b948-fcfbed1986e8" />

---

## Slicers Usage

Slicers were implemented to enhance data interaction:

- Added slicers for **Year**, **Product group**, and **Producer**
- Enabled dynamic filtering
- Improved dashboard usability
- Simplified comparative analysis

Slicers allow quick exploration of patterns without modifying Pivot Tables.

---
## Dashboard 

<img width="1111" height="725" alt="image" src="https://github.com/user-attachments/assets/72dda5d7-49c5-443e-91c9-9fbde4ef1c52" />

---

## Key Insights

1. Certain product groups consistently outperform others across multiple years.
2. Sales volume shows clear fluctuations between years, indicating seasonal or market trends.
3. A small number of producers dominate overall sales performance.
4. The best-selling outlet/store significantly exceeds others in volume contribution.
5. Some product groups demonstrate rapid growth, suggesting emerging demand.

---

## Recommendations

- Increase inventory for top-performing product groups.
- Strengthen partnerships with high-performing producers.
- Investigate strategies used by the best-selling outlet/store.
- Reassess underperforming product categories.
- Implement targeted marketing for growing product groups.

---

## Conclusion

Using Pivot Tables and slicers, raw sales data was successfully transformed into meaningful insights. The analysis highlights performance drivers, sales patterns, and opportunities for strategic decision-making.

---

