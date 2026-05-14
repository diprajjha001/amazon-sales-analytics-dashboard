# 🛒 Amazon Sales Dashboard | Power BI Project

![Amazon Sales Dashboard Banner](wide_promotional_banner_hero_image_for_a_power_b.png)

## 📌 Project Overview

The **Amazon Sales Dashboard** is an interactive Power BI project designed to analyze and visualize Amazon sales performance across products, cities, states, sellers, and order statuses.

This dashboard transforms raw e-commerce data into meaningful business insights through dynamic KPIs, trend analysis, and geographical visualizations. It helps stakeholders monitor performance, identify sales patterns, and make data-driven business decisions efficiently.

---

# 📊 Dashboard Features

## 🔹 Overview Page

The Overview page provides a high-level summary of sales performance with:

* Total Sales KPI
* Seller Count Analysis
* Order Status Filtering
* Sales by City
* Sales by State
* Interactive Product Slicer
* Time-based Sales Trend Analysis

### Key Insights:

* Track overall business growth
* Identify top-performing cities and states
* Analyze shipment and delivery status
* Monitor daily sales fluctuations

---

## 🔹 Product Page

The Product page focuses on product-level analysis and performance tracking.

### Includes:

* Product-wise sales analysis
* Product category insights
* Revenue contribution by products
* Product performance comparison
* Seller-level breakdown

---

## 🔹 Product View Page

This page provides a detailed visual breakdown of selected products.

### Includes:

* Product-specific KPIs
* Product trend analysis
* Detailed filtering experience
* Dynamic visual interaction

---

## 🔹 Product Tooltip Page

A custom tooltip page designed to enhance user interaction.

### Features:

* Dynamic hover tooltips
* Additional contextual insights
* Cleaner report navigation experience

---

# 🎯 Project Objectives

The primary objectives of this project are:

* Analyze Amazon sales performance efficiently
* Identify high-performing regions and products
* Monitor shipment and delivery status
* Create interactive business intelligence reports
* Improve decision-making using data visualization

---

# 📈 Key KPIs Used

| KPI            | Description                    |
| -------------- | ------------------------------ |
| Total Sales    | Overall revenue generated      |
| Seller Count   | Total active sellers           |
| Sales by City  | Revenue generated city-wise    |
| Sales by State | Revenue generated state-wise   |
| Order Status   | Shipment and delivery tracking |
| Product Sales  | Product-wise revenue analysis  |

---

# 🛠️ Tools & Technologies Used

| Tool        | Purpose                           |
| ----------- | --------------------------------- |
| Power BI    | Data Visualization & Dashboarding |
| Power Query | Data Cleaning & Transformation    |
| DAX         | Data Modeling & Calculations      |
| Excel / CSV | Data Source                       |

---

# 📂 Project Structure

```bash
📁 Amazon-Sales-Dashboard
│
├── 📄 amazon.pbix
├── 📄 README.md
├── 📁 Assets
│   ├── Dashboard_Screenshot.png
│   ├── Banner.png
│
└── 📁 Dataset
    └── Amazon_Sales_Data.csv
```

---

# 📷 Dashboard Preview

## 🖥️ Main Dashboard

### Features Highlighted:

✅ Interactive filters & slicers
✅ Sales trend visualization
✅ City & state-wise analytics
✅ Product performance analysis
✅ Shipment tracking insights
✅ Modern UI design

---

# 📌 Business Insights Generated

* Bengaluru generated the highest sales among cities.
* Maharashtra contributed the highest state-wise revenue.
* Sales trends fluctuated over time with visible growth peaks.
* Order shipment tracking helps identify operational bottlenecks.
* Product-level analysis improves inventory and marketing decisions.

---

# 🚀 Future Improvements

Potential future enhancements for this dashboard:

* Add customer segmentation analysis
* Include profit and margin KPIs
* Implement forecasting models
* Add drill-through analysis pages
* Integrate real-time data refresh

---

# 💡 Skills Demonstrated

This project demonstrates:

* Data Cleaning
* Data Modeling
* DAX Calculations
* Dashboard Design
* Business Intelligence
* Data Visualization
* Analytical Thinking
* UI/UX Design in Power BI

---

# 🔍 Key Power BI Concepts Used

## ✔ Data Modeling

Relationships between multiple tables were created for effective reporting.

## ✔ DAX Measures

Custom DAX measures were used for:

```DAX
Total Sales = SUM(Sales[Amount])
```

```DAX
Seller Count = DISTINCTCOUNT(Sales[Seller])
```

```DAX
Sales % = DIVIDE([Total Sales], CALCULATE([Total Sales], ALL(Sales)))
```

---

# 🎨 Dashboard Design Highlights

* Amazon-inspired orange theme
* Clean and modern layout
* Interactive navigation buttons
* Responsive visual arrangement
* KPI-focused design approach

---

# 📌 How to Use

1. Download the `.pbix` file
2. Open using Power BI Desktop
3. Refresh dataset if needed
4. Interact with slicers and visuals
5. Explore insights across pages

---

# 📥 Download Project

Clone this repository:

```bash
git clone https://github.com/your-username/amazon-sales-dashboard-powerbi.git
```

---

# 🤝 Connect With Me

If you liked this project, feel free to connect with me on LinkedIn and give this repository a ⭐.

---

# ⭐ Support

If you found this project helpful:

⭐ Star the repository
🍴 Fork the project
📢 Share with others

---

# 📜 License

This project is licensed under the MIT License.

---

# 📧 Contact

**Dipraj Jha**
Power BI Developer | Data Analyst | Continuous Learner
