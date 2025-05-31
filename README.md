# Exploratory Data Visualization of Chocolate Sales

**Author**: Cindy (Di) Chen  
**Date**: `r Sys.Date()`  
**Output Format**: PDF document (LaTeX engine: `xelatex`)  

## Overview
This project presents an exploratory data visualization analysis of chocolate sales data. The dataset includes transaction-level records with dates, products, amounts, and country-level information. The goal is to identify key sales trends across time, geography, and product categories to inform business decisions related to inventory and marketing.

## Objectives
- Analyze **country-level revenue performance**
- Explore **monthly/seasonal sales trends**
- Identify **top-selling products** to support inventory prioritization

## Key Steps
- Cleaned inconsistent date formats using `lubridate::dmy`
- Parsed and converted currency-formatted strings to numeric
- Removed duplicates and missing values
- Created clear, annotated, and colorblind-friendly `ggplot2` visualizations

## Visual Insights

### 1. Total Amount by Country
- **Australia** leads in sales, followed by the **UK**, **India**, **USA**, **Canada**, and **New Zealand**.
- Findings challenge assumptions about the US being the top market, prompting further regional investigation.

### 2. Monthly Sales Trend
- Sales **peak in January**, dip in **February**, and fluctuate through the summer.
- January’s post-holiday peak and March’s rise inform potential promotional strategies.

### 3. Top 10 Selling Products
- **“Smooth Silky Salty”** is the highest-grossing item, followed by **“50% Dark Bites”** and **“White Choc”**.
- These products should be prioritized for inventory during peak sales periods.

## Tools & Packages
- `tidyverse`, `lubridate`, `dplyr`, `stringr`, `scales`
- Visualizations built with `ggplot2`, formatted for clarity and accessibility

