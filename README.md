# Growth & Reliability Analytics for a UPI Payments Platform

## Project Overview

Unified Payments Interface (UPI) has become the backbone of digital payments in India. As transaction volume and user adoption continue to grow, payment platforms must optimize both operational reliability and user engagement.

This project simulates a real-world fintech product analytics use case by analyzing UPI transaction data and engineering user-level product dimensions to uncover insights related to transaction reliability, user behavior, retention, segmentation, platform performance, and growth opportunities.

Synthetic user-level attributes were engineered using realistic fintech behavioral assumptions to simulate real-world product analytics scenarios.

The project combines operational analytics with product analytics to identify opportunities for improving payment success rates, customer engagement, platform reliability, and long-term user retention.

---

## Business Problem

Transaction failures, user drop-offs, inconsistent engagement, platform-specific performance issues, and abnormal transaction behavior can negatively impact customer trust, retention, and revenue.

This project aims to answer key business questions such as:

* What drives transaction failures?
* Which banks, transaction types, or payment apps contribute most to failures?
* Which users are highly engaged or at risk of churn?
* How do verified users behave differently from non-verified users?
* Which payment apps drive higher engagement and retention?
* What merchant categories generate the highest activity?
* When do peak transaction periods occur?
* Which user segments contribute most to platform growth?

---

## Project Objectives

This project aims to:

* Analyze overall UPI transaction trends
* Measure transaction success and failure patterns
* Analyze Daily Active Users (DAU), Weekly Active Users (WAU), and Monthly Active Users (MAU)
* Measure user retention and repeat transaction behavior
* Perform cohort analysis using user signup dates
* Identify power users and transaction frequency segments
* Analyze engagement and transaction behavior across payment apps
* Analyze transaction reliability across banks and transaction types
* Compare verified vs non-verified user behavior
* Compare Android vs iOS transaction behavior
* Analyze merchant category behavior
* Identify peak transaction periods
* Detect unusual transaction patterns and operational anomalies
* Generate product and operational recommendations

---

## Dataset

### Primary Dataset

File:

`upi_transactions_2024.csv`

Contains transaction-level attributes such as:

* Transaction ID
* Transaction Timestamp
* Transaction Amount
* Transaction Status
* Bank Details
* Transaction Type

---

### Synthetic Product Enrichment

To simulate real-world product analytics scenarios, additional user-level dimensions were synthetically engineered using realistic fintech behavioral assumptions.

Engineered attributes:

* `user_id`
* `app_name`
* `user_signup_date`
* `kyc_status`
* `device_type`
* `merchant_category`

These engineered fields are created solely for analytical modeling and portfolio simulation purposes.

---

## Project Pipeline

```text
Raw Data
   ↓
Synthetic Data Enrichment
   ↓
Data Cleaning & Validation
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
SQL Business Analysis
   ↓
Product KPI Analysis
   ↓
Statistical Analysis & Anomaly Detection
   ↓
Dashboard Development
   ↓
Business Recommendations
