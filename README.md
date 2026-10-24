# Olist E-Commerce Analytics Dashboard

A comprehensive Power BI business intelligence solution designed to analyze Brazilian e-commerce performance using the public **Olist Store** dataset. This dashboard provides end-to-end visibility into executive sales metrics, seller/payment behaviors, and delivery fulfillment efficiencies.

---

## 📁 Download Project File
Since the `.pbix` file exceeds GitHub's standard file size limits, you can download the complete Power BI file directly from Google Drive:
👉 **[Download Olist eCommerce Analytics Dashboard (.pbix)](https://drive.google.com/file/d/17sABwTde6VTux-CKEsLNgVm98h0LUGH3/view?usp=sharing)**

---

## 📊 Dashboard Preview

### 1. Executive Overview
Provides a high-level summary of the overall business health, tracking core KPIs like total revenue, order volumes, customer acquisition, and review trends.
* **Key Metrics:** $13.59M Total Revenue | 99K Orders | 4.09 Avg Review Score | 96K Unique Customers
* **Highlights:** Top product categories by revenue (`health_beauty`, `watches_gifts`), monthly revenue trends, and overall on-time vs. late delivery split.

### 2. Sellers & Payments Performance
Deep-dives into marketplace dynamics, evaluating regional seller distribution, high-performing vendors, payment methods, and installment plan metrics.
* **Key Metrics:** R$ 15.84M Total GMV | R$ 120.65 Avg Item Price | 3K Active Sellers
* **Highlights:** Geographic performance breakdown (dominated by São Paulo - SP), transaction counts across payment types (`credit_card`, `boleto`, `voucher`), and order volumes by installment duration.

### 3. Delivery Performance
Analyzes logistics execution, carrier punctuality, regional transit bottlenecks, and the direct correlation between delivery delays and customer satisfaction scores.
* **Key Metrics:** 93.2% On-Time Rate | R$ 22.79 Avg Freight Value | 12.5 Days Avg Delivery Time
* **Highlights:** Comparison of review scores for on-time vs. delayed shipments, highest states by average delivery duration, and monthly delivery volume trends.

---

## 🛠️ Key Technical Features & Implementation

* **Data Modeling:** Built on a structured star/snowflake schema connecting orders, items, payments, customers, and geolocation datasets.
* **DAX Measures:** Custom measures developed for dynamic aggregation (e.g., GMV calculations, delivery lead times, on-time delivery percentages, and moving averages).
* **Power Query ETL:** Data cleaning, merging, and type transformation handled via Power Query to ensure optimal performance.
* **UI/UX Design:** Dark-mode executive theme crafted with custom background layouts, intuitive navigation cards, and clear visual hierarchy.

---

## 📂 Dataset Source
The data utilized in this project is sourced from the publicly available [Kaggle: Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), covering real orders made at Olist Store between 2016 and 2018.

---
