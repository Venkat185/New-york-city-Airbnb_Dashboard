# New-york-city-Airbnb_Dashboard

A data analysis and visualization project exploring the **New York City Airbnb marketplace** using the `AB_NYC_2019` dataset.  
The project uncovers patterns in **pricing, demand, room types, seasonality, and host performance** across boroughs and neighborhoods.

## 📊 Dashboard Overview

![NYC Airbnb Dashboard](Dashboard%201.png)

---

## 📌 Project Overview
This project analyzes **48,895 Airbnb listings** across **221 NYC neighborhoods** to understand how location and room type influence price and demand.  
The analysis highlights NYC as a **two-core Airbnb market (Manhattan & Brooklyn)** with distinct dynamics in outer boroughs.

---

## 🎯 Objectives
- Analyze **average prices** by borough and neighborhood
- Compare **booking demand** by room type and location
- Examine **seasonality trends** using review activity
- Identify **top-performing hosts** by total reviews
- Highlight **neighborhood-level price disparities**, especially in Brooklyn

---

## 📂 Dataset
- **Source:** Inside Airbnb  
- **File:** `AB_NYC_2019.csv`
- **Listings:** 48,895  
- **Hosts:** 37,457  
- **Total Reviews:** 1,138,005  

### Key Columns
- `price`
- `neighbourhood_group`
- `neighbourhood`
- `room_type`
- `number_of_reviews`
- `reviews_per_month`
- `last_review`
- `host_name`

---

## 🛠️ Methodology
1. **Data Cleaning**
   - Parsed `last_review` into datetime format
   - Handled missing values in review-related fields
2. **Feature Engineering**
   - Extracted review month from `last_review`
   - Aggregated metrics at borough and neighborhood levels
3. **Analysis**
   - Pricing comparison across boroughs
   - Demand estimation using reviews per month
   - Host performance ranking by total reviews
4. **Visualization**
   - Treemaps, heatmaps, bar charts, donut charts
   - Geographic price distribution map
   - Consolidated analytical dashboard

---

## 📊 Key Insights
- **Manhattan** has the highest average price (~$197).
- **Brooklyn** nearly matches Manhattan in listing volume.
- **Entire homes/apartments** dominate bookings across all boroughs.
- **Bronx and Queens** show higher utilization at lower prices.
- **June–July** is the peak Airbnb season.
- Brooklyn contains both the **most expensive** and **most affordable** neighborhoods.
- High-performing hosts optimize **occupancy over premium pricing**.

---

## 🧠 Tools & Technologies
- Tableau
- Excel
- Git & GitHub

---

## 📁 Repository Structure
