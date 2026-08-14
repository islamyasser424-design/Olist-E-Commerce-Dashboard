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
# E-Commerce Data Analytics: Insights & Dashboards

An end-to-end e-commerce data analytics project featuring interactive dashboards, detailed data insights, financial reconciliations, order breakdowns, and fulfillment analytics.

---

## 📌 Project Overview

This project provides comprehensive dashboards and actionable analytical insights to evaluate financial, operational, and delivery performance across key business dimensions:
1. **Overview Insights & Financial Performance:** Revenue, net profit, gross margin, payment reconciliation, and revenue variance.
2. **Order Breakdown Insights:** Detailed order lifecycle status, monthly delivered order trends, payment reconciliation status, and installment distribution.
3. **Delivery Insights:** Shipping delay metrics, late delivery revenue impacts, monthly fulfillment performance, and delay time tracking.

---

## 📊 Summary Key Performance Indicators (KPIs)

### 💵 Financial KPIs
* **Total Revenue:** `$15,419,774`
* **Total Payments Received:** `$15,271,774`
* **Expected Revenue:** `$15,735,527`
* **% Revenue Reconciliation (Actual vs. Expected):** `97.99%`
* **Net Profit:** `$11,023,222`
* **Gross Margin %:** `71.49%`
* **Payment Variance:** `$115,138`

### 📦 Order KPIs
* **Total Orders:** `99,441`
* **Total Delivered Orders:** `96,478`
* **Canceled Orders:** `625`
* **Canceled Orders Revenue Loss:** `$105,886`
* **Average Order Value (AOV):** `$155.06`

### 🚚 Delivery KPIs
* **Late Deliveries:** `7,826` orders
* **Late Deliveries Revenue Impact:** `$1,351,625`
* **Average Delay Time:** `10 days`

---

## 🔍 Detailed Insights & Dashboards Breakdown

### 1. Order Breakdown Insights & Dashboard

![Screenshot 2026-08-14 013733.png](Screenshot%202026-08-14%20013733.png)

#### Orders Detailed Status
* **Delivered:** `96,478` (97.02%)
* **Shipped:** `1,107`
* **Canceled:** `625` (1.24%)
* **Unavailable:** `609`
* **Invoiced:** `314`
* **Processing:** `301`
* **Created:** `5`
* **Approved:** `2`
* **Total:** `99,441` (100.00%)

#### Total Delivered Orders by Month
* **January:** 7,819
* **February:** 8,208
* **March:** 9,549
* **April:** 9,101
* **May:** 10,295 *(Peak delivery month)*
* **June:** 9,234
* **July:** 10,031
* **August:** 10,544 *(Highest volume)*
* **September:** 4,151
* **October:** 4,743
* **November:** 7,289
* **December:** 5,514

#### Payment Status Breakdown (Delivered Orders)
* **Correct Payment:** `75,901`
* **Underpaid:** `11,277`
* **Overpaid:** `9,299`

#### Installments Distribution
* **1 Installment:** `47,899` orders
* **2 - 5 Installments:** `35,409` orders
* **6 - 10 Installments:** `15,701` orders
* **10+ Installments:** `432` orders

---

### 2. Overview Insights & Dashboard (Financial Performance)

![Screenshot 2026-08-14 013740.png](Screenshot%202026-08-14%20013740.png)

#### Revenue & Net Profit by Month
| Month | Total Revenue ($) | Expected Revenue ($) | Net Profit ($) |
| :--- | :---: | :---: | :---: |
| **January** | $1,205,370 | $1,238,863 | $867,517 |
| **February** | $1,237,408 | $1,263,048 | $883,913 |
| **March** | $1,534,929 | $1,578,275 | $1,090,181 |
| **April** | $1,523,691 | $1,562,097 | $1,104,716 |
| **May** | $1,695,626 | $1,728,397 | $1,238,140 |
| **June** | $1,502,029 | $1,520,034 | $1,053,974 |
| **July** | $1,594,106 | $1,618,537 | $1,105,010 |
| **August** | $1,631,324 | $1,658,877 | $1,155,229 |
| **September** | $701,221 | $717,549 | $513,848 |
| **October** | $797,608 | $816,111 | $579,538 |
| **November** | $1,153,364 | $1,172,192 | $822,167 |
| **December** | $843,098 | $861,546 | $608,990 |
| **Grand Total** | **$15,419,774** | **$15,735,527** | **$11,023,222** |

#### Net Profit by Payment Method
* **Credit Card:** `$8,771,596` (Primary revenue & profit generator)
* **Boleto:** `$1,889,683`
* **Voucher:** `$214,630`
* **Debit Card:** `$147,314`

---

### 3. Delivery Insights & Dashboard (Fulfillment Performance)

![Screenshot 2026-08-14 013750.png](Screenshot%202026-08-14%20013750.png)

#### Late Delivery & Delay Analysis by Month
| Month | Late Deliveries | Late Deliveries Revenue ($) | Avg Delay Time (Days) |
| :--- | :---: | :---: | :---: |
| **January** | 487 | $91,282 | 11 |
| **February** | 1,101 | $175,079 | 12 |
| **March** | 1,638 | $272,894 | 11 |
| **April** | 542 | $103,343 | 10 |
| **May** | 684 | $113,071 | 7 |
| **June** | 204 | $53,115 | 12 |
| **July** | 409 | $77,534 | 8 |
| **August** | 799 | $118,997 | 4 |
| **September** | 217 | $35,541 | 9 |
| **October** | 240 | $40,576 | 8 |
| **November** | 1,043 | $173,430 | 10 |
| **December** | 462 | $96,762 | 9 |
| **Grand Total / Avg** | **7,826** | **$1,351,625** | **10 Days** |

#### Delivery Status Summary
* **Not Late:** `88,652`
* **Late:** `7,826`
* **Not Delivered:** `2,963`

---

## 🛠️ Project Structure & Workbook Worksheets

The Excel file/data model is structured into sheets connecting dashboards with raw data:
* `Order Breakdown insights` / `Order Breakdown Dashboard`
* `Overview insights` / `Overview Dashboard`
* `Delivery insights` / `Delivery Dashboard`
* `Data ...` (Raw data source & calculated measure fields)

---

## 💡 Strategic Key Recommendations

1. **Optimize Supply Chain & Bottlenecks:** Address logistics issues in March and February, which accounted for the highest number of late deliveries and revenue at risk.
2. **Promote Preferred Payment Gateways:** Credit cards account for over 79% of net profits. Incentivize direct digital payment channels to minimize reconciliation variances.
3. **Minimize Underpayments & Payment Anomalies:** Over `11,000` orders recorded underpayment status; implementing automated payment verification triggers at checkout will reduce revenue leakage.
