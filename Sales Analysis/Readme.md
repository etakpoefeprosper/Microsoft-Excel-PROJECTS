# Excel Sales Data Analysis Using Pivot Tables

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

### Top 5 Best-Selling Product Groups (2011–2014)

**Method:**

- Filtered Year → 2011–2014
- Rows → Product group
- Values → Sum of Volume
- Applied Top 5 filter

**Purpose:**  
To determine overall high-performing categories across the selected period.

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

### Top 10 Producers (2011–2014)

**Method:**

- Filtered Year → 2011–2014
- Rows → Producer
- Values → Sum of Volume
- Applied Top 10 filter

**Purpose:**  
To evaluate supplier performance.

---

## Slicers Usage

Slicers were implemented to enhance data interaction:

- Added slicers for **Year**, **Product group**, and **Producer**
- Enabled dynamic filtering
- Improved dashboard usability
- Simplified comparative analysis

Slicers allow quick exploration of patterns without modifying Pivot Tables.

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

