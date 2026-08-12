# Boat E-Commerce Dashboard

## 📌 Project Overview
This project features a comprehensive, interactive Business Intelligence dashboard designed to analyze e-commerce performance. It tracks key metrics across customer demographics, revenue streams, and product return logistics, providing actionable insights into purchasing behavior and product quality.

## 📊 Key Dashboards & Features

### 1. Customer Report
*   **High-Level KPIs:** Tracks total revenue (₹135.04M), total customers (12K), average revenue per customer, and average customer age.
*   **Geographic & Channel Analysis:** Visualizes customer distribution across India and ranks order channels (e.g., Amazon, Quick Commerce, Flipkart).
*   **Payment Preferences:** Highlights preferred transaction methods, showing a strong user preference for UPI and Credit Cards.

### 2. Revenue (Amount) Report
*   **Financial Metrics:** Monitors total profit (₹16.83M), average discount rates, and return revenue (₹4.69M).
*   **Category Performance:** Identifies top-performing product categories, with a clear breakdown showing "Boatproduct" as the leading revenue driver.
*   **Time-Series Trends:** Tracks monthly revenue trajectories to identify seasonal peaks and low periods.

### 3. Product & Return Report
*   **Quality Control:** Analyzes 89.06K total products sold against 4,500 returns.
*   **Return Reason Matrix:** Categorizes specific defect reasons (e.g., battery issues, damaged in transit, Bluetooth not working) across different product lines.
*   **Customer Sentiment:** Aggregates product reviews, showing the percentage of "Excellent," "Good Quality," and "Decent" ratings to gauge overall satisfaction.

## 🛠️ Data Architecture & Logic
The underlying data model relies on well-structured relational schemas (DDL) to organize the customer, product, and transaction tables efficiently. Data transformation and metric calculations heavily utilize conditional logic and comparison operators to accurately categorize return reasons, filter by specific product segments, and aggregate monthly trends. 

## 🚀 How to Use
1. Clone the repository to your local machine.
2. Open the main dashboard file (e.g., `.pbix` for Power BI or equivalent).
3. Use the left-hand navigation panel to switch between the **Customer**, **Revenue**, and **Product & Return** reports.
4. Utilize the dropdown filters (like the "Category" slicer) to dynamically update the visuals for targeted analysis.

## 📁 Repository Contents
*   `data/`: Contains the raw and cleaned datasets (or sample data).
*   `dashboards/`: The primary dashboard files.
*   `assets/`: Screenshots and screen recordings demonstrating the dashboard's interactivity.

---
*Created by [Gyan Prakash Vishwakarma]*
