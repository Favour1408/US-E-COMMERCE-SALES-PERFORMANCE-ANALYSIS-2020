# US-E-COMMERCE-SALES-PERFORMANCE-ANALYSIS-2020
## Table of Contents

- [Project Overview](#project-overview)
- [Project objective](#project-objective)
- [Dataset used](#dataset-used)
- [Problem Statement](#problem-statement)
- [Dataset Overview](#dataset-overview)
- [Data Preparation and Cleaning](#data-preparation-and-cleaning)
- [Dashboard Interactivity](#dashboard-interactivity)
- [Dashboard preview](#dashboard-preview)
- [Insights](#insights)
- [Recommendations](#recommendations)



## Project Overview

This project analyzes US e commerce sales data for the year 2020 to evaluate overall business performance. The analysis focuses on sales trends, profit behavior, customer segments, shipping methods, and regional performance.

## Project Objective
The objective of the project is to understand why the business recorded losses despite generating strong sales and to provide data driven insights that support better decision making.

## Dataset used
https://github.com/Favour1408/US-E-COMMERCE-SALES-PERFORMANCE-ANALYSIS-2020/blob/main/US%20%20E-commerce%20records%202020.xlsx


## Problem Statement

Despite achieving high sales revenue in 2020, the business ended the year with an overall loss.

This analysis seeks to answer the following business questions:

* Why did high sales volume not translate into profit
* Which products and categories contributed most to losses
* How shipping methods affected operational costs
* Which customer segments were profitable or unprofitable
* Which regions contributed positively or negatively to profit

---

## Dataset Overview

The dataset contains US e commerce transactional sales records for 2020.

Key fields in the dataset include:

* Order Date
* Product Category and Sub Category
* Sales
* Profit
* Discount
* Customer Segment
* Shipping Mode
* Region, State, and City

The dataset includes both revenue and cost related information required for performance evaluation.

---

## Data Preparation and Cleaning

Before analysis, the dataset was checked to ensure it was consistent and ready for reporting.

The dataset was already cleaned, therefore only minimal preparation was required.

The following steps were performed:

* Checked for missing values and inconsistencies before analysis
* Converted the Order Date column to the correct date format
* Created additional time based columns for analysis
* Calculated **Year**, **Month**, and **Day** from the Order Date column

The Year column was calculated using the formula:

```
=TEXT([@[Order Date]],"YYYY")
```

Similar formulas were used to derive the Month and Day columns.

These calculated fields enabled proper time trend analysis and interactive dashboard filtering.

---

## Dashboard Interactivity

An interactive Excel dashboard was created to allow users explore the dataset dynamically.

The dashboard includes:

* Year filter
* Month slicer
* Region slicer
* State and city filters
* KPI cards displaying total sales, total profit, discount, and profit margin

This interactivity allows users to quickly identify trends, performance gaps, and problem areas across different business dimensions.

## Dashboard Preview

## Insights

### Overall Performance

The business generated total sales of $28,278.70 but recorded a total loss of $2,074.26. This indicates that revenue growth alone was not sufficient to maintain profitability.

Profit varied significantly across months. Some months recorded positive profit while others experienced losses, with April showing the highest negative performance. This suggests periods of aggressive discounting or increased operational costs.

---

### Product Performance

Technology was the highest revenue generating category. However, high sales volume did not always translate into profit.

At the sub category level, Machines recorded the highest sales. These products are high cost items, and discounts applied to them had a strong negative impact on overall profit.

Other sub categories such as Chairs, Phones, and Tables recorded stable sales but could not offset losses from heavily discounted high value products.

---

### Shipping Method Performance

Shipping analysis showed a clear relationship between delivery speed and profitability.

First Class shipping generated the highest profit, indicating cost efficiency.

Same Day shipping recorded the highest losses despite strong sales volume. Second Class shipping also contributed to negative profit.

Fast delivery options significantly increased fulfillment costs and reduced margins.

---

### Customer Segment Performance

The Corporate segment generated the highest sales but also recorded the largest loss. This indicates heavy discounting and pricing concessions for large customers.

Consumer and Home Office segments generated lower sales volume but remained profitable. The Home Office segment showed strong profit relative to its sales.

This demonstrates that high volume customers are not always the most profitable.

---

### Regional Performance

The South region recorded significant losses and contributed the largest negative profit.

The Central and West regions performed positively, while the East region showed minimal profit contribution.

This indicates the need for region specific pricing and cost management strategies.

---

## Recommendations

### Optimize Discount Strategy

Discounting played a major role in reducing profitability, especially for high value technology products.

It is recommended that:

* Discount limits be applied to high cost items
* Margin based discount rules be introduced
* Blanket promotional discounts be reduced

This will help protect profit margins while maintaining competitive pricing.

---

### Review Fast Shipping Options

Same Day and Second Class shipping consistently generated losses.

The business should:

* Restrict Same Day shipping to premium or high margin orders
* Introduce additional delivery fees to cover fulfillment costs
* Limit fast shipping options to selected regions

This can significantly reduce unnecessary operational expenses.

---

### Reevaluate Corporate Customer Pricing

Although Corporate customers generated high revenue, they were largely unprofitable.

Recommended actions include:

* Reviewing negotiated pricing agreements
* Reducing excessive bulk discounts
* Setting minimum profit thresholds for large orders

This ensures large volume sales contribute positively to profit.

---

### Improve Regional Cost Management

Losses in the South region indicate structural cost issues.

The business should:

* Review logistics and shipping costs within the region
* Adjust pricing strategies by location
* Optimize delivery routes and fulfillment processes

Targeted regional optimization can reduce recurring losses.

---

### Focus on Profitable Segments

Consumer and Home Office segments demonstrated stable profitability.

The business should:

* Increase marketing efforts toward profitable segments
* Strengthen customer retention strategies
* Focus on margin driven growth rather than volume driven growth

This supports long term business sustainability.



## Author

**Animam Favour**
Data Analyst

Blog: [https://favour1408.hashnode.dev](https://favour1408.hashnode.dev)



