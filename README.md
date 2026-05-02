# Laptop Market & Customer Insights Analysis

## Overview

This project analyzes a laptop dataset to extract both business and customer insights. It is divided into two main dashboards:

1. Sales & Market Analysis Dashboard
2. Customer Preferences Dashboard

The goal is to understand market performance, product distribution, and user behavior.

---

## Objectives

* Identify top-performing laptop brands in the market
* Analyze hardware component distribution (CPU, GPU, Storage)
* Understand customer preferences in terms of RAM, screen type, and weight
* Provide insights that support decision-making for product positioning

---

## Dataset

The dataset contains information about laptops including:

* Brand (Company)
* Type (Notebook, Gaming, Ultrabook, etc.)
* CPU and GPU brands
* RAM size
* Storage type (SSD, HDD, Hybrid, Flash)
* Screen specifications
* Weight

---

## Dashboards

### 1. Sales & Market Analysis

This dashboard focuses on revenue-based insights:

* Top performing companies by revenue
* GPU market share distribution
* Storage type contribution to total sales
* Most popular operating system
* Product type performance

### Key Insights:

* Certain brands dominate overall revenue, with a clear gap between top and mid-tier companies
* GPU distribution shows strong dominance by a few key players
* SSD storage significantly leads in total sales compared to other storage types
* Notebooks represent the most sold product category

---

### 2. Customer Preferences Analysis

This dashboard focuses on user behavior and product usage (count-based analysis):

* Most popular laptop brands among users
* Most used CPU brands
* Distribution of RAM sizes across brands
* Preferred screen types
* Preferred laptop weight ranges

### Key Insights:

* A few brands are significantly more popular among users in terms of ownership
* Intel processors are the most commonly used, while alternatives have minimal adoption
* 8GB RAM appears to be the most common configuration across multiple brands
* Full HD screens (1920x1080) are the most preferred by users
* Most users prefer lightweight laptops within a specific weight range

---

## Tools Used

* Microsoft Excel (Dashboard Design & Visualization and transform raw columns to usable columns )
* Python (Data Cleaning & Preprocessing)
  * Pandas
    
---

## Project Structure

* `laptop_price_cleaned.csv` → Cleaned dataset
* `dash1` → Sales & Market Dashboard
* `dash2` → Customer Preferences Dashboard

---

## Conclusion

This project provides a combined view of:

* Market performance (revenue perspective)
* Customer behavior (usage perspective)

Such analysis helps in:

* Identifying best-selling configurations
* Understanding user needs
* Supporting better product and marketing strategies

---

## Author

Youssef Aly
