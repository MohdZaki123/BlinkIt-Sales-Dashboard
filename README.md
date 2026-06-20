# 🛒 BlinkIT Grocery Sales Dashboard 📊

## 📌 Project Overview

This interactive **Power BI Dashboard** provides a comprehensive analysis of **BlinkIT Grocery Sales Data**, helping stakeholders understand customer purchasing behavior, product performance, sales trends, and delivery efficiency. The dashboard transforms raw retail data into actionable business insights through interactive visualizations and KPI tracking.

### 🎯 Objectives

* Monitor category-wise and product-wise sales performance.
* Analyze delivery efficiency across different cities.
* Understand customer purchasing patterns.
* Identify top-performing and underperforming products.
* Track key business metrics through dynamic dashboards.

---

## 🖼️ Dashboard Preview

> Add dashboard screenshots here

![Dashboard Screenshot](images/dashboard.png)

---

## 📂 Dataset Information

**Dataset Used:** `BlinkIT Grocery Data.xlsx`

The dataset contains information related to:

* Order Details
* Product Categories
* Product Names
* City-wise Orders
* Delivery Performance
* Revenue Metrics
* Sales Transactions

### Dataset Columns

| Column Name          | Description             |
| -------------------- | ----------------------- |
| Order ID             | Unique order identifier |
| Product Category     | Category of the product |
| Product Name         | Product purchased       |
| City                 | Delivery city           |
| Delivery Time (mins) | Delivery duration       |
| Quantity             | Units sold              |
| Price                | Unit price              |
| Total Sales          | Revenue generated       |
| Order Date           | Date of purchase        |

---

## 🛠️ Tools & Technologies

* **Power BI** – Data Visualization & Dashboard Development
* **Microsoft Excel** – Data Source
* **DAX (Data Analysis Expressions)** – KPIs & Calculated Measures
* **Power Query Editor** – Data Cleaning & Transformation

---

## ✨ Dashboard Features

### 🚚 Delivery Performance Analysis

* Average delivery time by city
* Delivery performance by product category

### 🏙️ City-wise Sales Analysis

* Revenue comparison across cities
* Highest and lowest performing cities

### 📦 Product Performance Tracking

* Top-selling products
* Product category breakdown
* Revenue contribution by SKU

### 💰 Revenue Insights

* Total revenue trends over time
* Dynamic filtering by city and category

### 📅 Time-Based Analysis

* Monthly sales trends
* Custom date range filtering

### 🔍 Interactive Drill-Down

* Explore data at category, product, and city levels
* Dynamic slicers for deeper analysis

---

## 🧹 Data Cleaning & Transformation

The following preprocessing steps were performed:

* Removed null and missing values
* Converted delivery time into numeric format
* Standardized city names and product categories
* Created calculated sales metrics
* Extracted Year and Month from Order Date

### Calculated Column

```DAX
Total Sales = Quantity * Price
```

---

## 📊 Key Performance Indicators (KPIs)

The dashboard tracks the following KPIs:

* 💰 Total Revenue
* 📦 Total Orders
* 🚚 Average Delivery Time
* 🏆 Top 5 Product Categories by Sales
* ⚡ City with Fastest Delivery
* 📉 Slowest Performing City

---

## 📈 Business Insights

### Key Findings

* Delivery time significantly impacts customer satisfaction in metro cities.
* Packaged food and daily essentials contribute the highest revenue.
* Tier-1 cities generally achieve faster delivery times than Tier-2 cities.
* Seasonal trends influence demand for specific product categories.
* High-performing products account for a substantial share of overall sales.

---

## 📁 Project Structure

```plaintext
BlinkIT-Grocery-Sales-Dashboard/
│
├── blinkit.pbix
├── BlinkIT Grocery Data.xlsx
├── images/
│   └── dashboard.png
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

* Power BI Desktop installed on your system.

### Steps

1. Clone this repository:

```bash
git clone https://github.com/yourusername/BlinkIT-Grocery-Sales-Dashboard.git
```

2. Open `blinkit.pbix` using Power BI Desktop.

3. Refresh the dataset or connect your own updated Excel file.

4. Use filters, slicers, and drill-through functionality to explore insights.

---

## 📌 Project Use Case

This project demonstrates how **Business Intelligence (BI)** tools can be used in the retail and grocery industry to:

* Improve operational efficiency
* Monitor delivery performance
* Increase revenue visibility
* Support data-driven decision-making

---

## 👨‍💻 Author

**Mohammed Zaki Attar**

📧 Email: [mohdzakiattar@gmail.com](mailto:mohdzakiattar@gmail.com)

💼 LinkedIn: Add Your LinkedIn Profile Link

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## 📄 License

This project is intended for educational and portfolio purposes.
