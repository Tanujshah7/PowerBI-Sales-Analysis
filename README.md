# Power BI Sales Analysis Dashboard

This repository contains a Power BI dashboard created as part of an assignment to analyze sales data.

## Dataset Source  
The dataset used in this project was sourced from a YouTube tutorial:  
[🔗 YouTube Video](https://youtu.be/6cV3OwFrOkk?si=tzwK2IuMOGGsgYlq).  
The original data was provided for educational purposes, and I have used it to create a Power BI dashboard.

## Dataset Overview  
The data consists of sales transactions, including customer details, order details, and financial metrics.

- **details.csv**:
  - `Order ID`
  - `Amount` (Sales)
  - `Profit`
  - `Quantity`
  - `Category`
  - `Sub-Category`
  - `Payment Mode`

- **order.csv**:
  - `Order ID`
  - `Order Date`
  - `Customer Name`
  - `State`
  - `City`

## Data Cleaning & Transformation
1. Imported CSV files into Power BI.
2. Merged datasets using `Order ID` as the key.
3. Created a new column **Profit Margin** using the formula: Profit Margin = (Profit / Sales) * 100
4. Applied filters to display customers with a profit margin >10%.

## Visualizations in Dashboard
- **Table:** Displays top 5 customers by total sales.
- **Bar Chart:** Sales by product category.
- **Line Chart:** Monthly sales trends.
- **Donut Chart:** Distribution of sales by payment mode.
- **Horizontal Bar Chart:** Top 5 sub-category products by profit.
- **Interactive Buttons:** Filters data by city and state.

## How to Use
- Open `Assignment of Power BI.pbix` in Power BI.
- Explore the dashboard and apply filters to analyze different trends.

## Screenshots
(Screenshot previews of the dashboard)

## Author
Created by **Tanuj Shah**.
