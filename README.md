# Product Analytics for User Activation, Retention, and Growth in a UPI Payments Ecosystem

## Project Overview

Unified Payments Interface (UPI) has become the backbone of digital payments in India, processing millions of transactions daily across consumer and merchant ecosystems.

As competition among digital payment platforms intensifies, sustainable product growth increasingly depends on:

- Strong onboarding experiences
- Fast user activation
- High repeat transaction behavior
- Long-term user retention
- High-value user engagement
- Reduced lifecycle drop-offs
- Strong merchant ecosystem participation

This project simulates a real-world fintech product analytics use case by analyzing transaction-level UPI data enriched with user-level behavioral dimensions to identify the product, behavioral, and lifecycle drivers of activation, retention, churn, and power-user engagement.

The project applies product analytics, behavioral analytics, funnel analysis, cohort modeling, churn analytics, quasi-experimentation, and product instrumentation to generate actionable product recommendations for growth and retention optimization.

---

## Executive Business Problem

India’s UPI ecosystem processes millions of digital transactions daily, where sustained user engagement, seamless onboarding, transaction trust, and repeat payment behavior directly influence platform growth, ecosystem expansion, and long-term monetization.

While transaction success rates remain consistently high, variations in:

- onboarding behavior
- KYC completion
- first transaction behavior
- merchant engagement
- transaction frequency
- platform usage patterns
- device-specific behavior

may significantly impact:

- user activation
- repeat usage
- retention
- churn risk
- high-value engagement

This project aims to identify these behavioral and product-level drivers and translate findings into actionable product decisions.

---

## Business Context

UPI platforms create sustainable growth through:

- Strong onboarding experiences
- Fast activation
- Frequent user engagement
- Repeat transaction behavior
- Merchant ecosystem participation
- Long-term retention
- High-value user monetization

Core business risks include:

- Low signup-to-activation conversion
- Weak KYC completion
- Poor first-week transaction behavior
- Early lifecycle drop-offs
- Low repeat transaction frequency
- Platform-specific engagement gaps
- Limited merchant ecosystem diversity
- High user churn risk

---

## Core Product Journey

```text
Signup
↓
KYC Completion
↓
First Successful Transaction
↓
Second Transaction
↓
Repeat Usage
↓
Habit Formation
↓
Power User Engagement
```

---

## Product Funnel Framework

This project explicitly measures drop-offs across critical lifecycle stages:

```text
Signup
↓
KYC Completion
↓
First Successful Transaction
↓
Second Transaction
↓
7-Day Active
↓
30-Day Retained
```

### Funnel Metrics

- Signup → KYC Conversion Rate
- KYC → First Transaction Conversion Rate
- First → Second Transaction Conversion Rate
- First-Week Activation Rate
- 7-Day Retention Rate
- 30-Day Retention Rate
- Stage-wise Drop-off Rate

---

## Project Objectives

This project aims to support product decision-making through the following analytical objectives:

### User Growth & Engagement

- Identify overall transaction growth trends, seasonality, and engagement patterns
- Measure Daily Active Users (DAU)
- Measure Weekly Active Users (WAU)
- Measure Monthly Active Users (MAU)
- Measure Monthly Active Transacting Users (MATU)
- Analyze transaction frequency and engagement intensity

### Activation & Funnel Optimization

- Measure signup-to-KYC conversion
- Measure KYC-to-first-transaction conversion
- Measure first-to-second transaction conversion
- Identify lifecycle drop-offs
- Identify onboarding friction points

### Retention & Cohort Analysis

- Perform cohort analysis using signup dates
- Measure first-week activation
- Measure 7-day retention
- Measure 30-day retention
- Analyze repeat transaction behavior

### User Segmentation

- Identify casual users
- Identify repeat users
- Identify power users
- Identify high-value users

### Behavioral Analytics

- Analyze merchant diversity
- Analyze payment app engagement
- Analyze bank-level engagement
- Analyze platform-specific behavior
- Analyze device-specific behavior

### Churn Analytics

- Identify churn risk indicators
- Predict users likely to become inactive
- Analyze behaviors associated with churn

### Quasi-Experimentation

- Identify product optimization opportunities
- Simulate observational product experiments
- Estimate impact of behavioral interventions

### Product Instrumentation

- Design inferred product event taxonomy
- Identify product event tracking gaps
- Recommend event instrumentation strategy

---

## Strategic Business Priorities

### Priority 1 — Improve User Activation

Goal:

Understand how signup timing, KYC completion, and first transaction behavior influence early activation.

Business Impact:

- Improved onboarding efficiency
- Reduced acquisition waste
- Higher activation

---

### Priority 2 — Improve User Retention

Goal:

Identify behavioral patterns associated with repeat usage and long-term engagement.

Business Impact:

- Reduced churn
- Higher retained users
- Increased transaction volume

---

### Priority 3 — Identify High-Value Users

Goal:

Understand behaviors associated with:

- Power users
- High-frequency users
- High-value users

Business Impact:

- Better monetization
- Loyalty optimization
- Merchant ecosystem growth

---

### Priority 4 — Reduce Funnel Drop-Off

Goal:

Identify major drop-off stages across onboarding and activation.

Business Impact:

- Improved conversion
- Reduced abandonment
- Faster activation

---

### Priority 5 — Predict Churn Risk

Goal:

Identify users likely to become inactive.

Business Impact:

- Early intervention
- Reduced churn
- Improved lifecycle retention

---

### Priority 6 — Identify Product Experiment Opportunities

Goal:

Evaluate behavioral cohorts to identify product improvement opportunities.

Business Impact:

- Data-driven optimization
- Feature prioritization
- Conversion improvement

---

## Dataset

### Primary Dataset

File:

`upi_transactions_2024.csv`

Contains transaction-level attributes such as:

- transaction_id
- transaction_timestamp
- transaction_amount
- transaction_status
- bank_details
- transaction_type

---

### Synthetic Product Enrichment

Additional user-level dimensions were engineered to simulate real-world product analytics scenarios:

- `user_id`
- `app_name`
- `user_signup_date`
- `kyc_status`
- `device_type`
- `merchant_category`

These engineered attributes were created solely for analytical modeling and portfolio simulation purposes.

---

## Analytical Hypotheses

### H1

Users completing KYC exhibit higher activation and retention.

### H2

Users completing a successful first-week transaction show higher repeat behavior.

### H3

Power users transact across more merchant categories than casual users.

### H4

Android and iOS users demonstrate different engagement patterns.

### H5

Users with higher transaction frequency show stronger monthly retention.

### H6

Users engaging across multiple merchant categories exhibit higher long-term engagement.

### H7

Users completing second transactions within 7 days demonstrate lower churn.

### H8

Users with higher merchant diversity exhibit stronger retention.

### H9

KYC-completed users demonstrate lower funnel drop-off.

### H10

High-frequency users demonstrate lower churn probability.

---

## Quasi-Experimentation Framework

### Experiment 1

KYC Completed vs Non-KYC Users

Metrics:

- First-week activation
- 30-day retention

---

### Experiment 2

Android vs iOS Users

Metrics:

- Transaction frequency
- Retention

---

### Experiment 3

Low Merchant Diversity vs High Merchant Diversity

Metrics:

- Monthly retention
- Transaction frequency

---

### Experiment 4

Early Second Transaction vs Delayed Second Transaction

Metrics:

- Churn probability
- Long-term retention

---

## Churn Framework

### Churn Definition

A user with no successful transaction activity in the next 30 days.

### Churn Features

- Recency
- Transaction frequency
- Monetary value
- Merchant diversity
- KYC completion
- Platform usage
- Device type

### Churn Deliverables

- Churn segmentation
- Churn prediction model
- Feature importance analysis

---

## Product Event Taxonomy (Inferred)

### Lifecycle Events

- signup_completed
- kyc_completed
- first_transaction_success
- second_transaction_success
- repeat_transaction
- churn_risk_detected

### Transaction Events

- payment_success
- payment_failed
- merchant_expansion
- high_value_transaction

### Behavioral Events

- power_user_unlocked
- category_expansion
- retention_milestone

---

## Project Pipeline

```text
Raw Data
↓
Synthetic Product Enrichment
↓
Data Cleaning & Validation
↓
Feature Engineering
↓
SQL Metric Layer
↓
Funnel Analysis
↓
Cohort Analysis
↓
Retention Analysis
↓
Churn Modeling
↓
Quasi Experimentation
↓
Dashboard Development
↓
Product Recommendations
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

- Python
- SQL
- Jupyter Notebook
- pandas
- NumPy
- Statistical Analysis
- Machine Learning
- Power BI / Tableau

---

## North Star Metrics

- Monthly Active Transacting Users (MATU)
- Transactions per Active User
- First-Week Activation Rate
- 30-Day Retention Rate
- Funnel Conversion Rate
- Churn Rate
- Power User Rate

---

## Supporting Metrics

- Daily Active Users (DAU)
- Weekly Active Users (WAU)
- Monthly Active Users (MAU)
- Repeat Transaction Rate
- Merchant Diversity Score
- Average Transaction Value
- Transaction Frequency
- Platform Engagement Rate

---

## Deliverables

This project will deliver:

- Cleaned analytical fact table
- SQL metric layer
- Funnel dashboard
- Cohort models
- Retention models
- Churn prediction models
- User segmentation models
- Experimentation analysis
- Event taxonomy framework
- Executive dashboard
- Product KPI dashboard
- Product recommendations
- Portfolio case study
- Interview-ready storytelling deck

---

## Author

**Aniket Koli**

Aspiring Product Analyst | Data Analyst | Fintech Product Analytics
