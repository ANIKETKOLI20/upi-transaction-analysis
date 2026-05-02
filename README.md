# Growth & Reliability Analytics for a UPI Payments Platform

## Project Overview

Unified Payments Interface (UPI) has become the backbone of digital payments in India. As transaction volume and user adoption continue to grow, payment platforms must optimize both operational reliability and user engagement.

This project simulates a real-world fintech product analytics use case by analyzing UPI transaction data and engineering user-level product dimensions to uncover insights related to transaction reliability, user behavior, retention, segmentation, and platform performance.

The project combines operational analytics with product analytics to identify opportunities for improving payment success rates, customer engagement, and platform growth.

---

## Business Problem

Transaction failures, user drop-offs, inconsistent engagement, platform-specific performance issues, and abnormal transaction behavior can negatively impact customer trust, retention, and revenue.

This project aims to answer questions such as:

* What drives transaction failures?
* Which banks or transaction types contribute most to failures?
* Which users are highly engaged?
* How do verified users behave differently?
* Which payment apps drive higher engagement?
* What merchant categories generate the highest activity?
* What user segments contribute most to platform growth?

---

## Project Objectives

* Analyze transaction success and failure patterns
* Measure platform reliability metrics
* Analyze Daily Active Users (DAU), Weekly Active Users (WAU), and Monthly Active Users (MAU)
* Perform retention and cohort analysis
* Identify power users and repeat transaction behavior
* Compare payment app performance
* Analyze user behavior by KYC status
* Compare Android vs iOS engagement
* Analyze merchant category behavior
* Detect anomalies and operational bottlenecks

---

## Dataset

### Original Dataset

File:

`upi_transactions_2024.csv`

Contains transaction-level attributes such as:

* Transaction ID
* Timestamp
* Transaction Amount
* Transaction Status
* Bank Details
* Transaction Type

---

### Synthetic Product Enrichment

To simulate real-world product analytics scenarios, additional user-level dimensions were engineered using realistic fintech assumptions.

Engineered attributes:

* `user_id`
* `app_name`
* `user_signup_date`
* `kyc_status`
* `device_type`
* `merchant_category`

These attributes are created solely for analytical modeling and portfolio simulation.

---

## Project Pipeline

```text
Raw Data
   ↓
Synthetic Data Enrichment
   ↓
Data Cleaning & Validation
   ↓
SQL Analysis
   ↓
Product KPI Analysis
   ↓
Dashboard Development
   ↓
Business Recommendations
```

---

## Project Structure

```text
upi-product-analytics/
│
├── data/
│   ├── raw/
│   ├── enriched/
│   └── processed/
│
├── notebooks/
├── sql/
├── dashboard/
├── docs/
├── scripts/
├── README.md
└── project_charter.md
```

---

## Technologies Used

* Python
* Jupyter Notebook
* pandas
* NumPy
* SQL
* Dashboard Tool (To be added)

---

## Current Status

### Completed

* Project Charter
* Folder Structure
* Dataset Loading
* Synthetic Product Data Enrichment

Completed engineered attributes:

* user_id
* app_name
* user_signup_date
* kyc_status
* device_type
* merchant_category

---

## Next Steps

* Data Cleaning
* Missing Value Analysis
* Duplicate Analysis
* Outlier Detection
* Feature Engineering
* SQL Business Analysis
* Product KPI Analysis
* Cohort Analysis
* Retention Analysis
* Dashboard Development

---

## Key Product Metrics (Planned)

* DAU
* WAU
* MAU
* Retention Rate
* Repeat Transaction Rate
* Success Rate
* Failure Rate
* Power User Ratio
* App Adoption Rate
* KYC Conversion Rate

---

## Author

**Aniket Koli**

Aspiring Product Analyst | Data Analyst | Fintech Analytics
