# Tesla Sales Analytics Dashboard — Power BI

## 📊 Project Overview

This project presents an interactive **Tesla Sales Analytics Dashboard built in Microsoft Power BI** using a dataset of **75,971 Tesla sales transactions**.

The dashboard transforms raw sales data into an interactive business intelligence solution that helps analyze **sales volume, revenue, customer demographics, geographic performance, model popularity, color preferences, sales channels, and yearly revenue trends**.

The goal of the project is to demonstrate how Power BI can be used to convert a large transactional dataset into a visually engaging dashboard that supports business-oriented decision making.

---

## 🚗 Dataset Overview

The dataset contains **75,971 sales records** and 20 original attributes covering:

* Tesla Model
* Vehicle Color
* Manufacturing Year
* Sale Year
* State
* Sale Price
* Customer Age
* Gender
* Sales Channel
* Payment Method
* Delivery Status
* Delivery Days
* Battery Capacity
* Driving Range
* Charging Time
* Service Plan
* Warranty
* Referral Code
* Trade-in Usage

The Power BI model also derives an **Age Group** field for demographic analysis.

---

## 📌 Key Dashboard KPIs

| KPI                      |              Value |
| ------------------------ | -----------------: |
| Units Sold               |         **75,971** |
| Total Revenue            | **$4.177 Billion** |
| Average Revenue per Sale |        **$54,987** |
| States Covered           |              **6** |
| Tesla Models             |              **5** |
| Sales Years              |      **2018–2024** |

---

## 🔎 Key Insights

### 1. Model Performance

**Model 3** is the clear volume leader with **30,515 units**, representing approximately **40.2%** of all sales.

It is followed by:

* Model Y — **26,591 units (35.0%)**
* Model X — **7,557 units (9.9%)**
* Model S — **7,496 units (9.9%)**
* Cybertruck — **3,812 units (5.0%)**

Model 3 and Model Y together account for approximately **75% of total unit sales**, showing a strong concentration around Tesla's higher-volume models.

### 2. Geographic Performance

California is the strongest market with **26,477 sales**, approximately **34.9%** of the dataset.

Texas follows with **18,863 sales (24.8%)**.

Together, California and Texas contribute nearly **60% of total sales volume**, making them the dominant markets in this dataset.

### 3. Color Preference

**White** is the most popular vehicle color with **22,976 units (30.2%)**, followed by:

* Black — 19,096
* Silver — 14,983
* Blue — 11,280
* Red — 7,636

White and Black together represent more than **55% of all vehicle sales**.

### 4. Sales Channel

Online sales dominate the sales mix:

* Online — **45,555 / 60.0%**
* In-store — **22,918 / 30.2%**
* Third-party Dealer — **7,498 / 9.9%**

This indicates that digital/direct sales are the primary channel in the dataset.

### 5. Customer Demographics

The customer base is relatively balanced by gender:

* Male — **52.9%**
* Female — **47.1%**

The largest age segment is **18–28**, representing approximately **19.2%** of sales.

The remaining major age groups are relatively evenly distributed, suggesting that Tesla sales are not concentrated exclusively in one older demographic.

### 6. Payment Behavior

Leasing is the most common payment method:

* Lease — **40.0%**
* Cash — **30.1%**
* Loan — **29.9%**

The distribution shows a relatively diversified financing mix, with leasing holding a modest lead.

### 7. Revenue Trend

Revenue increased substantially from **2018 through 2022**, reaching its highest point in 2022 at approximately **$1.038B**.

Revenue then declined in 2023 and 2024.

The important observation is that this movement is primarily driven by **sales volume**, because average sale price remains remarkably stable at around **$55K** across the years.

### 8. Delivery Performance

Approximately **80.2%** of transactions are marked as delivered.

* Delivered — 60,922
* Pending — 11,337
* Cancelled — 3,712

This provides an additional operational perspective beyond pure sales performance.

---

## 🎯 Dashboard Features

The Power BI dashboard includes:

* KPI cards for Units Sold, Revenue and Average Revenue
* Gender distribution donut chart
* Sales channel distribution
* Model distribution
* State-wise sales column chart
* Age-group sales analysis
* Revenue-by-year trend
* Model × Color sales matrix
* Interactive Model slicer
* Interactive Color slicer
* Interactive State slicer
* Sale Year filtering
* Custom Tesla-themed dashboard design

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Data Visualization**
* **CSV / Excel-style tabular data**
* **Business Intelligence & Analytics**

---

## 💡 Business Story

The dashboard tells a clear story:

> Tesla's sales performance in this dataset is driven primarily by high-volume Model 3 and Model Y sales, with California and Texas acting as the strongest markets. Online sales are the dominant purchasing channel, White and Black are the most preferred colors, and leasing is the leading payment method. Revenue grows strongly through 2022 before declining, while the average selling price remains relatively stable, indicating that changes in revenue are largely associated with changes in sales volume rather than major changes in unit pricing.

---

## ⚠️ Data Quality Note

During analysis, **13 transactions were identified with negative Sale Price values**, contributing approximately **-$45.8K** to total revenue.

These records should be reviewed before using the dataset for financial reporting or production-level business decisions. They may represent refunds, adjustments, data-entry errors, or synthetic-data anomalies.

---

## 📁 Project Files

* `Tesla Car Data.csv` — Source sales dataset
* `Tesla Sales Analytics Dashboard.pbix` — Power BI dashboard
* `Tesla Sales Analytics Dashboard.png` — Dashboard preview

---

## 👨‍💻 Project Objective

This project demonstrates an end-to-end business intelligence workflow:

**Raw Data → Data Preparation → Data Modeling → KPI Development → Interactive Visualization → Business Insights**

The project is designed as a portfolio example for demonstrating practical **Power BI, data analytics, dashboard design, and business storytelling skills**.
