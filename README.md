# 🍔 Food Delivery Executive KPI Dashboard

## 📊 Veda Technology – Data Analytics Internship

### Task 26 – Executive KPI Dashboard

This project was developed as part of the Veda Technology Data Analytics Internship.

The objective of this task is to create a one-page executive management dashboard with dynamic filters, KPI cards, charts, and business insights using a Food Delivery Operations dataset.

---

## 🎯 Project Objective

The main objective of this project is to analyze food delivery operations and present important business performance indicators through an interactive executive dashboard.

The dashboard helps management understand:

- Revenue performance
- Order volume
- Customer behavior
- Delivery performance
- Payment preferences
- Food category performance
- Cancellation rate

---

## 🗂️ Dataset

A custom Food Delivery Operations dataset was created for this project.

### Dataset Columns

| Column | Description |
|---|---|
| Order ID | Unique order identifier |
| Order Date | Date of the order |
| City | Customer/order city |
| Restaurant Type | Type of restaurant |
| Food Category | Category of food ordered |
| Customer Type | New, regular, or premium customer |
| Payment Mode | Payment method |
| Order Amount | Order revenue |
| Delivery Time | Delivery duration in minutes |
| Customer Rating | Customer rating |
| Order Status | Delivered or cancelled |
| Month | Month extracted from order date |

---

## 📌 Key Performance Indicators

The dashboard contains the following KPIs:

### 💰 Total Revenue

Total revenue generated from all food delivery orders.

**Formula:**

`SUM(Order Amount)`

### 🛵 Total Orders

Total number of unique food delivery orders.

**Formula:**

`COUNT DISTINCT(Order ID)`

### ⏱️ Average Delivery Time

Average delivery time for successfully delivered orders.

**Formula:**

`AVERAGE(Delivery Time)`

### ⭐ Average Customer Rating

Average rating provided by customers.

**Formula:**

`AVERAGE(Customer Rating)`

### ❌ Cancellation Rate

Percentage of orders that were cancelled.

**Formula:**

`Cancelled Orders / Total Orders × 100`

### 💵 Average Order Value

Average revenue generated per order.

**Formula:**

`Total Revenue / Total Orders`

---

## 📊 Dashboard Features

The interactive dashboard includes:

- Dynamic City filter
- Dynamic Food Category filter
- Dynamic Customer Type filter
- Dynamic Payment Mode filter
- Total Revenue KPI
- Total Orders KPI
- Average Delivery Time KPI
- Average Customer Rating KPI
- Cancellation Rate KPI
- Average Order Value KPI
- Monthly Revenue Trend
- Revenue by City
- Revenue by Food Category
- Orders by Customer Type
- Payment Mode Distribution
- Average Delivery Time by City

---

## 📈 Visualizations

### 1. Monthly Revenue Trend

Shows how food delivery revenue changes over time.

### 2. Revenue by City

Compares revenue generated from different cities.

### 3. Revenue by Food Category

Shows the contribution of different food categories to total revenue.

### 4. Orders by Customer Type

Compares orders from new, regular, and premium customers.

### 5. Payment Mode Distribution

Shows the distribution of different payment methods.

### 6. Average Delivery Time by City

Helps compare delivery performance between cities.

---

## 🔎 Dynamic Dashboard

The dashboard contains interactive filters.

Users can select:

```text
City
Food Category
Customer Type
Payment Mode
