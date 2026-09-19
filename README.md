# Customer-Shopping-Trends-Analysis
An end-to -end data analytics project that analyses customer purchasing patterns to uncover segments, trends, and drivers of revenue, with the goal of informing marketing, merchandising, and retention strategy using **Python** (cleaning the dataset & feature engineering), **MySQL** (structured business queries) and **PowerBI** (interactive dashboard visualization).


## Table of Contents
- [Overview](#overview)
- [Business Questions](#business-questions)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Setup](#setup)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project analyzes retail transactions from 10000 Indian customers over 2years to understand how different customer groups shop, what they buy, and what drives repeat purchases. It covers data cleaning, exploratory analysis, customer segmentation, and visualization of results.

## Business Questions

- Who are our most valuable customers, and what do they have in common?
- How do purchase frequency and spend vary by age, gender, location, or membership status?
- Which product categories drive the most revenue and repeat purchases?
- How do discounts, promotions, and seasonality affect buying behavior?
- Which customer segments are at risk of churning?

## Dataset

| Field | Description |
|---|---|
| transactionr_id | Unique transaction identifier |
| customer_id | Unique customer identifier |
| purchase_date | Purchasing dates |
| age | Customer age |
| gender | Customer gender |
| location | Customer Cities |
| category | Product category |
| item_purchased | Product name |
| brand | Product brand |
| color | Product Color |
| size | Product size |
| Quantity | Product quantity |
| purchase_amount | Transaction value (INR) |
| discount(%)| percentage of discount applied on the MRP |
| festival\sale | standard day or a festival day |
| season | Season of purchase |
| review_rating | Customer rating (1-5) |
| payment_method | Payment type |

| previous_purchases | Count of prior purchases |
| frequency_of_purchases | Purchase cadence (weekly, monthly, etc.) |

*Size:* [10000] x [26]
*Time range:* [01-01-2023] to [31-12-2024]


## Project Structure
