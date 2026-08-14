# 🛒 Olist E-Commerce Performance & Logistics Dashboard

A comprehensive interactive dashboard for analyzing financial performance, orders, and logistics for **Olist** (one of the largest e-commerce platforms in Brazil). This dashboard is designed to help decision-makers track revenues, identify logistical bottlenecks, and optimize the customer experience.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Key Performance Indicators (KPIs)](#-key-performance-indicators-kpis)
- [Dashboards Breakdown](#-dashboards-breakdown)
  - [1. Financial Performance Dashboard](#1-financial-performance-dashboard)
  - [2. Order Breakdown Dashboard](#2-order-breakdown-dashboard)
  - [3. Delivery & Logistics Dashboard](#3-delivery--logistics-dashboard)
- [Key Insights & Recommendations](#-key-insights--recommendations)
- [Tech Stack & Tools](#-tech-stack--tools)

---

## 📊 Project Overview

This project provides an end-to-end analytical study of Olist's operational data across 3 primary dashboards:
1. **Financial Performance (Overview Dashboard):** Tracks revenue stream, net profits, and collection rates.
2. **Order Breakdown Dashboard:** Analyzes order volumes, payment status, and installment behaviors.
3. **Delivery & Logistics Dashboard:** Monitors shipping delays, average delay times, and financial risk caused by late deliveries.

---

## 📈 Key Performance Indicators (KPIs)

| Metric | Value | Description |
| :--- | :--- | :--- |
| **Total Revenue** | **$15,419,774** | Total gross sales generated |
| **Net Profit** | **$11,023,222** | Net earnings after operating costs |
| **Gross Margin** | **71.49%** | Overall profitability margin |
| **Total Orders** | **99,441** | Total number of customer orders |
| **Total Delivered Orders** | **96,478 (97.02%)** | Successful delivery fulfillment rate |
| **Average Order Value (AOV)** | **$155.06** | Average spending per order |
| **Late Orders** | **7,826** | Total orders delivered past target date |
| **Late Deliveries Revenue** | **$1,351,625** | Total value affected by delivery delays |
| **Avg Delay Time** | **10 Days** | Average delay period for late deliveries |

---

## 🖼️ Dashboards Breakdown

### 1. Financial Performance Dashboard

![Overview Dashboard](Overview%20Dashboard.png)

Focuses on fiscal evaluation and comparing actual collected revenue against expected earnings.
* **Key KPI Metrics:**
  * **Expected Revenue:** $15,735,527 vs. **Total Payments:** $15,271,774.
  * **% Revenue Collected:** 97.99%.
* **Visualizations:**
  * **Total Revenue by Month:** Line chart displaying monthly sales trends (peaking in May at $1,695,626).
  * **Revenue vs. Expected Revenue by Month:** Column chart comparing projected vs. actual revenue.
  * **Net Profit by Payment Type:** Distribution of net profit across payment methods (`Credit Card` leads with $8.77M, followed by `Boleto` at $1.88M).

---

### 2. Order Breakdown Dashboard

![Order Breakdown Dashboard](Order%20Breakdown%20Dashboard.png)

Analyzes order fulfillments, payment collection health, and installment plan breakdown.
* **Key KPI Metrics:**
  * **Canceled Orders:** 625 orders (valued at $105,886).
  * **Orders % by Status:** 97.02% Delivered, 1.74% Pending, and 1.24% Canceled.
* **Visualizations:**
  * **Total Delivered Orders by Month:** Monthly trend of completed fulfillments (highest volume in August with 10,544 orders).
  * **Orders Per Payment Status:** Payment health breakdown (Correct Payment: 75,901 | Underpaid: 11,277 | Overpaid: 9,299).
  * **Installments Breakdown:** Distribution of installment payments (1 Installment dominates with 47,899 orders, followed by 2–5 installments with 35,409).

---

### 3. Delivery & Logistics Dashboard

![Delivery Dashboard](Delivery%20Dashboard.png)

Dedicated to monitoring supply chain efficiency, shipping status, and delay impacts.
* **Key KPI Metrics:**
  * **Delivery Status Breakdown:** 88,652 On-time (Not late), 7,826 Late, and 2,963 Not Delivered.
* **Visualizations:**
  * **Late Delivery Orders by Month:** Monthly delay trends (March suffered the highest delay count with 1,638 late orders).
  * **Avg Delay Time by Month:** Monthly average delay in days (ranged between 4 to 12 days).
  * **Late Deliveries Revenue by Month:** Financial revenue exposed to shipping delay risks per month (March peaked at $272,894).

---

## 💡 Key Insights & Recommendations

1. **Payment Methods:** Customers heavily rely on **Credit Card** and **Boleto**. Promoting incentives for digital payment types (such as Debit Cards or Vouchers) could streamline cash flow.
2. **Installment Plans:** Over 50% of purchases involve installments (predominantly 2–5 installments). Expanding Buy-Now-Pay-Later (BNPL) options will likely drive conversion rates further.
3. **Logistics Bottlenecks:**
   * **March** was the worst performing month in terms of shipping delays and associated risk revenue.
   * The average delay time stands at **10 days**, which negatively impacts customer satisfaction. Renegotiating SLA agreements with regional courier partners is highly recommended.

---

## 🛠️ Tech Stack & Tools

* **Microsoft Excel :** Data transformation, modeling, and interactive dashboard UI design.
* **Slicers & Dynamic Filtering:** Time-period slicing (Months timeline) and side-navigation filtering by Payment Method & Order Status.
* **Data Modeling:** Integrated relational model across financial, order, and shipping tables.

---
