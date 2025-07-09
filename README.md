# 🏙️ Dubai Real Estate Intelligence PowerBI Dashboard

## 📌 Project Overview
This project presents an interactive Power BI dashboard built using real estate listings data from Dubai. The aim is to deliver actionable insights for **investors**, **agents**, and **policy makers** by analyzing price trends, property types, and geographic hotspots.

---

## 🎯 Objective
To help stakeholders make data-driven decisions in the Dubai real estate market by visualizing key metrics and trends in an intuitive, professional dashboard.

---

## 📁 Dataset Summary
The dataset includes 1,000 property listings with the following fields:
- `SquareFeet`
- `Bedrooms`
- `Bathrooms`
- `Neighborhood`
- `YearBuilt`
- `Price`

---

## 🛠️ Data Preparation (Power Query)
- Removed duplicates and cleaned missing/invalid entries.
- Converted data types to appropriate formats (e.g., price → numeric).
- Added calculated fields:
  - **PricePerSqft** = `Price / SquareFeet`
  - **PropertyAge** = `2025 - YearBuilt`
  - **ListingCategory**:
    - Budget (≤ 190,000 AED)
    - Mid-Range (190,001–270,000 AED)
    - High-End (> 270,000 AED)

---

## 📊 Dashboard Features
### 📌 Section 1: KPI Metrics
- Total Listings
- Average Price
- Average Price per Sqft
- Highest Priced Property
- Average Property Size

### 📌 Section 2: Visual Analytics
- Bar chart: Price by Property Type
- Stacked column: Listings by Bedroom & Property Type
- Tree Map: Developer vs Property Type
- Histogram: Property Age Distribution
- Pie Chart: Listing Category Distribution
- Scatter Plot: Price vs SquareFeet (by Listing Category)
- Line Chart: Price Trends (simulated if date unavailable)
- Map: Avg Price by Location (if location data is available)

### 📌 Section 3: Filters & Interactivity
- Slicers for:
  - Bedrooms
  - Bathrooms
  - Neighborhood
  - Listing Category
  - Price Range
- Tooltips and data drill-throughs for detailed exploration

---


## ✅ Tools Used
- **Power BI**
- **Power Query Editor**
- Basic DAX formulas for calculated columns

---
