# Online Retail Data Analysis

## Project Overview

This project performs an exploratory data analysis (EDA) on a real-world online retail transactions dataset. The goal is to extract business-relevant insights related to revenue trends, customer behavior, product performance, and geographic distribution using Python-based data analysis tools.

## Dataset

* **Source**: Online Retail dataset (UK-based e-commerce retailer)
* **Period**: December 2010 – December 2011
* **Granularity**: Transaction-level invoice data

Key fields include invoice number, product details, quantity, unit price, customer ID, country, and invoice date.

## Objectives

* Clean and prepare raw transactional data for analysis
* Analyze revenue evolution over time
* Identify customer purchasing patterns and repeat behavior
* Evaluate product-level performance
* Assess geographic concentration of revenue

## Tools & Technologies

* Python
* pandas
* matplotlib
* Jupyter Notebook

## Key Steps

1. **Data Ingestion & Cleaning**

   * Handled non-UTF8 encoding
   * Parsed datetime fields correctly
   * Removed returns, zero-priced items, and missing customer IDs

2. **Exploratory Analysis**

   * Revenue and transaction-level metrics
   * Monthly revenue time series (excluding incomplete periods)
   * Customer-level aggregation and repeat purchase analysis
   * Product and country-level revenue breakdown

3. **Visualization**

   * Monthly revenue trends
   * Top countries by revenue

## Key Insights

* Revenue increased steadily throughout 2011 with clear seasonality.
* A relatively small group of repeat customers contributes a large share of total revenue.
* Sales are highly concentrated in the UK, with international markets forming a long tail.
* Product sales follow a classic long-tail distribution.

## Project Structure

```
├── data/
│   └── raw/
│       └── Online_Retail.csv
├── notebooks/
│   └── online_retail_analysis.ipynb
├── README.md
```

## Next Steps

* Customer segmentation using RFM analysis
* Cohort and retention analysis
* Revenue forecasting and trend decomposition