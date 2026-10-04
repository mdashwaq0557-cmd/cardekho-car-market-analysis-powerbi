# cardekho-car-market-analysis-powerbi
# 🚗 CarDekho Car Market Analysis | Power BI Dashboard

An interactive Power BI dashboard designed to analyze used-car market performance across sales, pricing, brands, models, fuel types, cities, customer ratings and dealer profitability.

---

## 📊 Project Overview

The objective of this project is to transform used-car data into an interactive Business Intelligence dashboard that provides meaningful insights into market performance.

The dashboard allows users to explore:

- Sales performance
- Brand performance
- Model pricing
- Fuel-type preferences
- City-wise sales
- Monthly sales trends
- Customer ratings
- Dealer profitability
- Market-leading brands and cities

The project focuses on creating a clean, professional and interactive one-page Power BI dashboard.

---

## 🎯 Business Objectives

The main objectives of this project are:

1. Analyze overall used-car sales performance.
2. Identify the brands generating the highest sales.
3. Identify models with the highest average selling prices.
4. Analyze monthly sales trends.
5. Understand customer preferences by fuel type.
6. Identify cities with the highest sales.
7. Analyze average selling prices.
8. Evaluate dealer profitability.
9. Provide dynamic business insights using DAX.
10. Enable interactive analysis using slicers.

---

## 📁 Dataset

The dataset contains:

- 1,500 car records
- 31 analytical attributes

### Important Columns

| Column | Description |
|---|---|
| Car_ID | Unique car listing identifier |
| Listing_Date | Date of listing |
| Brand | Car manufacturer |
| Model | Car model |
| Variant | Vehicle variant |
| Manufacture_Year | Manufacturing year |
| Fuel_Type | Petrol, Diesel, CNG, Electric or Hybrid |
| Transmission | Manual, AMT, Automatic, DCT or CVT |
| Body_Type | Vehicle body type |
| Engine_CC | Engine capacity |
| Mileage_kmpl | Mileage |
| Color | Exterior color |
| Owner_Count | Number of previous owners |
| Kilometers_Driven | Distance driven |
| Condition | Vehicle condition |
| City | Listing city |
| State | Listing state |
| Seller_Type | Seller category |
| Price_Lakh | Reference price |
| Selling_Price_Lakh | Selling price |
| Acquisition_Cost_Lakh | Acquisition cost |
| Dealer_Margin_Lakh | Dealer margin |
| Customer_Rating | Customer rating |
| Demand_Index | Demand score |
| Warranty_Months | Warranty period |
| Insurance_Validity_Months | Insurance validity |
| Service_History | Service history |
| Accident_History | Accident history |
| Feature_Score | Vehicle feature score |
| Popularity_Score | Popularity score |
| Sales_Status | Sold, Available, Reserved or Under Inspection |

---

## 📌 Dashboard Features

### KPI Cards

The dashboard includes five key performance indicators:

- Total Cars
- Sold Cars
- Average Selling Price
- Average Customer Rating
- Profit Margin %

---

### 📈 Sales Trend

A monthly sales trend visualization is used to understand changes in vehicle sales over time.

---

### 🏆 Top 10 Brands by Sales

A horizontal bar chart identifies the top-performing car brands based on sold vehicles.

---

### 💰 Top 10 Models by Average Price

This visualization identifies the models with the highest average selling prices.

---

### ⛽ Sales by Fuel Type

A donut chart shows the distribution of sold vehicles across:

- Petrol
- Diesel
- Electric
- CNG
- Hybrid

---

### 📍 Top 5 Cities by Sales

A city-level analysis identifies the locations generating the highest vehicle sales.

---

## 🔎 Interactive Filters

Users can dynamically filter the dashboard using:

- Brand
- Fuel Type
- City
- Year
- Transmission

All major dashboard components respond to the selected filters.

---

## 💡 Live Business Insights

The dashboard contains three dynamic DAX-based insights:

### 1. Sales Leader

Identifies the brand with the highest number of sold vehicles.

### 2. Market Leader

Identifies the city with the highest sales.

### 3. Pricing Leader

Identifies the model with the highest average selling price.

These insights update dynamically based on the selected filters.

---

## 🧮 DAX Measures

Important measures used in the dashboard include:

### Total Cars

```DAX
Total Cars =
COUNTROWS(CarData)
