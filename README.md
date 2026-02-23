# 📊 E-Commerce Product & Customer Transaction Analysis

## 📌 Project Overview

This dataset contains integrated e-commerce transaction data combining **order, customer, product, seller, payment, and delivery information** in a single structured table.

Each row represents **one product within one order** (item-level transaction data).

This dataset is ideal for:

* Customer Segmentation (RFM, Revenue Tier)
* Customer Lifetime Value (CLV)
* Revenue & Payment Analysis
* Delivery Performance Analysis
* Geographic Sales Analysis
* Retention & Cohort Analysis

---

## 📂 Dataset Information

| Attribute        | Details                          |
| ---------------- | -------------------------------- |
| Total Rows       | 99,967 transactions              |
| Total Columns    | 23 columns                       |
| Unit of Analysis | 1 row = 1 product in 1 order     |
| Data Types       | Numerical, Categorical, DateTime |

---

## 🧾 Data Structure

### 🛒 Order Information

| Column                          | Description                              |
| ------------------------------- | ---------------------------------------- |
| `order_id`                      | Unique order identifier                  |
| `order_status`                  | Order status (delivered, canceled, etc.) |
| `order_purchase_timestamp`      | Purchase timestamp                       |
| `order_approved_at`             | Payment approval time                    |
| `order_delivered_timestamp`     | Actual delivery time                     |
| `order_estimated_delivery_date` | Estimated delivery date                  |

---

### 👤 Customer Information

| Column                     | Description                |
| -------------------------- | -------------------------- |
| `customer_id`              | Unique customer identifier |
| `customer_zip_code_prefix` | Customer ZIP code          |
| `customer_city`            | Customer city              |
| `customer_state`           | Customer state             |

---

### 📦 Product Information

| Column                  | Description            |
| ----------------------- | ---------------------- |
| `product_id`            | Product identifier     |
| `product_category_name` | Product category       |
| `product_weight_g`      | Product weight (grams) |
| `product_length_cm`     | Product length         |
| `product_height_cm`     | Product height         |
| `product_width_cm`      | Product width          |

---

### 🏪 Seller Information

| Column      | Description       |
| ----------- | ----------------- |
| `seller_id` | Seller identifier |

---

### 💳 Payment Information

| Column                 | Description             |
| ---------------------- | ----------------------- |
| `payment_sequential`   | Payment sequence number |
| `payment_type`         | Payment method          |
| `payment_installments` | Number of installments  |
| `payment_value`        | Total payment value     |

---

### 💰 Pricing Information

| Column             | Description   |
| ------------------ | ------------- |
| `price`            | Product price |
| `shipping_charges` | Shipping cost |

---

## 🔍 Business Objectives

This dataset can help answer strategic business questions such as:

### Revenue & Growth

* What is the monthly revenue trend?
* Which product categories generate the highest revenue?
* Which payment methods are most frequently used?

### Customer Analytics

* Who are the highest-value customers?
* How can customers be segmented based on revenue?
* What is the customer retention rate?

### Delivery Performance

* What is the average delivery time?
* What percentage of orders are delivered late?
* Which cities experience the highest delivery delays?

### Geographic Insights

* Which states generate the highest sales?
* Are there regional patterns in purchasing behavior?

---

## 📊 Recommended Analysis

### 1️⃣ RFM Segmentation

* **Recency** → Days since last purchase
* **Frequency** → Number of orders per customer
* **Monetary** → Total payment value per customer

### 2️⃣ Customer Lifetime Value (CLV)

* Total revenue per customer
* Average Order Value (AOV)
* Purchase frequency

### 3️⃣ Revenue Analysis

* Revenue by category
* Revenue by state
* Revenue by payment type

### 4️⃣ Delivery Analysis

* Delivery delay calculation
* On-time delivery rate
* Delivery performance by region

### 5️⃣ Cohort & Retention Analysis

* Monthly customer cohort
* Retention rate per cohort
* Repeat purchase behavior

---

## 🎯 Business Value

This analysis supports:

* Identifying high-value customers
* Improving delivery efficiency
* Optimizing product strategy
* Increasing customer retention
* Data-driven decision making

---
