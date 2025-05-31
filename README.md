# 🍫 Exploratory Data Visualization of Chocolate Sales

**Author**: Cindy Chen  
**Date**: Spring 2025

---

## 📄 Overview

This project explores chocolate sales data to uncover trends in geography, seasonality, and product performance. The analysis includes data wrangling, visual exploration, and design of accessible, polished plots using the `ggplot2` package in R.

---

## 🎯 Objectives

- Examine **country-level revenue** performance  
- Analyze **monthly/seasonal sales trends**  
- Identify **top-performing chocolate products**  
- Create **colorblind-friendly visualizations** with clear annotations  

---

## 🧾 Dataset Description

The dataset includes transaction-level chocolate sales records, with variables such as:

- `Date`: Transaction date  
- `Product`: Chocolate product name  
- `Amount`: Sale amount (currency)  
- `Country`: Country of sale  

Data was cleaned and transformed using `tidyverse`, `lubridate`, and `stringr`. Sales amounts were standardized, and missing/duplicate entries removed.

---

## 🔍 Methodology

### 1. Data Wrangling  
- Converted date strings using `lubridate::dmy()`  
- Removed duplicates and NA values  
- Cleaned and parsed currency formats to numeric

### 2. Visualization Strategy  
- Built three key plots using `ggplot2`  
- Applied consistent themes, labels, and colorblind-friendly palettes  
- Included direct annotations to highlight insights  

---

## 📊 Visualizations

### 🌍 Total Amount by Country  
- Top countries: **Australia**, **UK**, **India**, **USA**, **Canada**, **New Zealand**  
- 💡 Australia is the clear leader, suggesting regional demand differences  

### 📆 Monthly Sales Trend  
- 📈 Peak in **January** (post-holiday purchases), dip in **February**, recovery in **March**  
- 🏖️ Slower summer months — useful for inventory planning  

### 🍬 Top 10 Best-Selling Products  
- 🥇 "Smooth Silky Salty" is the #1 product  
- Others include "50% Dark Bites", "White Choc", "Orange Crunch", etc.  
- 💡 Clear candidates for promotional focus  

---

## 📦 Tools & Libraries

- **R packages**:  
  - `tidyverse`, `lubridate`, `stringr`, `scales`  
  - `ggplot2` for visualization  
- **Rendering**:  
  - `rmarkdown` with `xelatex` for high-quality PDF output  

---

## ✅ Key Insights

- 🌏 **Australia** consistently ranks highest in revenue  
- 📆 Clear **seasonal patterns**, with January as the sales peak  
- 🍫 Product rankings suggest **clear demand leaders** that warrant promotion or bulk stock

---

## 🚀 Future Work

- 📈 Build **forecast models** for monthly sales using time series  
- 🔍 Add demographic or marketing campaign data to explain peaks  
- 🌐 Create interactive dashboards for real-time business decision-making

---

## 📁 Deliverables

- 📄 PDF Report (includes code, visuals, and commentary)  
- 🧼 Fully reproducible R script (`chocolate_sales_viz.Rmd`)  
- 📊 Three finalized, annotated plots  

---
