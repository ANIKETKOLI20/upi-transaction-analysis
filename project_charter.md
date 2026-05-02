# PROJECT CHARTER

## 1. Project Name

**Growth & Reliability Analytics for a UPI Payments Platform**

---

## 2. Business Problem / Purpose

Unified Payments Interface (UPI) has become the backbone of digital payments in India. As transaction volume and user adoption continue to grow, payment platforms must optimize both operational reliability and user engagement.

Transaction failures, user drop-offs, inconsistent engagement, platform-specific performance issues, and abnormal transaction behavior can negatively impact customer trust, retention, and revenue.

This project aims to analyze UPI transaction data combined with engineered user-level product dimensions to identify user behavior patterns, transaction reliability issues, engagement drivers, operational bottlenecks, and actionable product opportunities that can improve platform growth, customer retention, and payment success rates.

---

## 3. Project Objectives

This project aims to:

* Analyze overall UPI transaction trends
* Measure transaction success and failure rates
* Analyze Daily Active Users (DAU), Weekly Active Users (WAU), and Monthly Active Users (MAU)
* Measure user retention and repeat transaction behavior
* Perform cohort analysis using user signup dates
* Identify power users and transaction frequency segments
* Analyze transaction behavior across payment apps, banks, and merchant categories
* Compare verified vs non-verified user behavior
* Compare Android vs iOS transaction behavior
* Identify peak transaction periods
* Detect unusual transaction patterns or anomalies
* Generate product and operational recommendations based on findings

---

## 4. Success Metrics / KPIs

The success of this project will be measured using the following KPIs:

* Overall transaction success rate (%)
* Overall transaction failure rate (%)
* Daily Active Users (DAU)
* Weekly Active Users (WAU)
* Monthly Active Users (MAU)
* User retention rate (%)
* Repeat transaction rate (%)
* Average transaction value
* Transaction frequency per user
* Failure rate by bank
* Failure rate by payment app
* Failure rate by merchant category
* Verified user conversion rate
* Platform-wise engagement rate
* High-value transaction percentage
* Anomaly detection rate

---

## 5. Project Scope

This project includes:

* Analysis of UPI transaction data for the year 2024
* Synthetic enrichment of user-level product dimensions
* Analysis of successful and failed transactions
* User lifecycle analysis
* Cohort analysis
* Retention analysis
* Transaction frequency analysis
* Payment app performance analysis
* Merchant category analysis
* Device segmentation analysis
* Exploratory data analysis (EDA)
* Statistical analysis
* Product analytics
* Operational analytics
* Data visualization
* Dashboard/report creation
* Business insight generation

---

## 6. Out of Scope

This project does not include:

* Real-time fraud prevention implementation
* Live payment gateway integration
* Production deployment
* Backend engineering implementation
* International payment analysis
* Credit/debit card transaction analysis
* Actual customer identity verification
* Regulatory compliance implementation

---

## 7. Data Sources

### Primary Dataset

* `upi_transactions_2024.csv`

### Original Dataset Attributes

* Transaction ID
* Transaction timestamp
* Transaction amount
* Transaction status
* Bank details
* Transaction type

### Engineered Product Analytics Attributes

To simulate real-world product analytics scenarios, additional user-level dimensions were synthetically engineered using domain assumptions and realistic fintech behavioral patterns.

Engineered attributes include:

* `user_id`
* `app_name`

  * Examples: Google Pay, PhonePe, Paytm
* `user_signup_date`
* `kyc_status`
* `device_type`
* `merchant_category`

These engineered fields are created solely for analytical modeling and portfolio simulation purposes and are not part of the original source dataset.

---

## 8. Deliverables

This project will deliver:

* Enriched analytical dataset
* SQL queries for product and business analysis
* Python-based exploratory data analysis
* User segmentation analysis
* Retention and cohort analysis
* Product KPI dashboard
* Operational KPI dashboard
* Statistical insights
* Anomaly detection insights
* Interactive visualizations
* Final product and operational recommendations report

---
