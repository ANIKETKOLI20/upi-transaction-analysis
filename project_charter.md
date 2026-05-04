# PROJECT CHARTER  
# Improving User Activation, Engagement, Retention, and Product Optimization in a UPI Payments Ecosystem

---

# 1. Executive Problem Statement

India’s digital payments ecosystem processes millions of UPI transactions daily, where sustained user engagement, seamless onboarding, transaction trust, and repeat payment behavior directly influence platform growth, ecosystem expansion, and long-term monetization.

While transaction success rates remain consistently high, variations in onboarding behavior, KYC completion, first transaction success, merchant engagement, transaction frequency, and platform interaction may significantly impact user activation, retention, churn risk, and high-value engagement.

This project aims to identify behavioral, lifecycle, and product-level drivers influencing user activation, repeat usage, retention, churn, and power-user behavior, and translate these findings into actionable product recommendations, experimentation opportunities, and product instrumentation strategies.

---

# 2. Business Context

UPI platforms create sustainable growth through:

- Strong onboarding experiences
- Fast activation
- Frequent user engagement
- Repeat transaction behavior
- Merchant ecosystem participation
- Long-term user retention
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

# 3. Core Product Journey

Signup  
→ KYC Completion  
→ First Successful Transaction  
→ Second Transaction  
→ Repeat Usage  
→ Habit Formation  
→ Power User Engagement

---

# 4. Product Funnel Framework

This project will explicitly measure drop-offs across key lifecycle stages:

Signup  
→ KYC Completion  
→ First Successful Transaction  
→ Second Transaction  
→ 7-Day Active  
→ 30-Day Retained

Funnel metrics:

- Signup to KYC Conversion Rate
- KYC to First Transaction Conversion Rate
- First to Second Transaction Conversion Rate
- First-Week Activation Rate
- 7-Day Retention Rate
- 30-Day Retention Rate
- Stage-wise Drop-off Rate

Business impact:

- Identify onboarding friction
- Reduce early abandonment
- Improve activation efficiency

---

# 5. Project Objectives

This project aims to support product decision-making by:

## User Growth & Engagement

- Identify overall transaction growth trends, seasonality, and engagement patterns
- Measure Daily Active Users (DAU), Weekly Active Users (WAU), Monthly Active Users (MAU), and Monthly Active Transacting Users (MATU)
- Analyze transaction frequency and engagement intensity

## Activation & Funnel Optimization

- Measure signup-to-KYC conversion
- Measure KYC-to-first-transaction conversion
- Measure first-to-second transaction conversion
- Identify lifecycle drop-offs

## Retention & Cohort Analysis

- Perform cohort analysis using signup dates
- Measure first-week activation
- Measure 7-day, 30-day retention
- Analyze repeat transaction behavior

## User Segmentation

- Identify casual users
- Identify repeat users
- Identify power users
- Identify high-value users

## Behavioral Analytics

- Analyze merchant diversity
- Analyze platform-specific behavior
- Analyze bank-specific engagement
- Analyze device-specific behavior

## Churn Analytics

- Identify churn risk indicators
- Predict users likely to become inactive
- Analyze behaviors associated with churn

## Experimentation Opportunities

- Identify product optimization opportunities
- Simulate quasi-experiments using behavioral cohorts
- Estimate impact of product changes

## Product Instrumentation

- Design inferred product event taxonomy
- Identify instrumentation gaps
- Recommend event tracking strategy

---

# 6. Strategic Business Priorities

## Priority 1 — Improve User Activation

Goal:

Understand how signup timing, KYC completion, and first transaction behavior influence early activation.

Business impact:

- Improved onboarding efficiency
- Reduced acquisition waste
- Higher activation

---

## Priority 2 — Improve User Retention

Goal:

Identify behavioral patterns associated with repeat usage and long-term engagement.

Business impact:

- Reduced churn
- Higher retained users
- Increased transaction volume

---

## Priority 3 — Identify High-Value Users

Goal:

Understand behaviors associated with:

- Power users
- High-frequency users
- High-value users

Business impact:

- Better monetization
- Loyalty optimization
- Merchant ecosystem growth

---

## Priority 4 — Reduce Funnel Drop-Off

Goal:

Identify major drop-off stages across onboarding and activation.

Business impact:

- Improved conversion
- Reduced abandonment
- Faster activation

---

## Priority 5 — Predict Churn Risk

Goal:

Identify users likely to become inactive.

Business impact:

- Early intervention
- Reduced churn
- Improved lifecycle retention

---

## Priority 6 — Identify Product Experiment Opportunities

Goal:

Evaluate behavioral cohorts to identify product improvement opportunities.

Business impact:

- Data-driven optimization
- Feature prioritization
- Conversion improvement

---

# 7. Decision Ownership / Stakeholders

- Product Management Team
- Growth Team
- Customer Experience Team
- Data Team
- Business Leadership

---

# 8. Analytical Hypotheses

## H1

Users completing KYC exhibit higher activation and retention.

## H2

Users completing a successful first-week transaction show higher repeat behavior.

## H3

Power users transact across more merchant categories than casual users.

## H4

Android and iOS users demonstrate different engagement patterns.

## H5

Users with higher transaction frequency show stronger monthly retention.

## H6

Users engaging across multiple merchant categories exhibit higher long-term engagement.

## H7

Users completing second transactions within 7 days demonstrate lower churn.

## H8

Users with higher merchant diversity exhibit stronger retention.

## H9

KYC-completed users demonstrate lower funnel drop-off.

## H10

High-frequency users demonstrate lower churn probability.

---

# 9. Quasi-Experimentation Framework

The project will simulate observational product experiments:

## Experiment 1

KYC Completed vs Non-KYC Users

Metrics:

- First-week activation
- 30-day retention

## Experiment 2

Android vs iOS Users

Metrics:

- Transaction frequency
- Retention

## Experiment 3

Low Merchant Diversity vs High Merchant Diversity

Metrics:

- Monthly retention
- Transaction frequency

## Experiment 4

Early Second Transaction vs Delayed Second Transaction

Metrics:

- Churn probability
- Long-term retention

---

# 10. Churn Framework

Churn Definition:

A user with no successful transaction activity in the next 30 days.

Churn features:

- Recency
- Transaction frequency
- Monetary value
- Merchant diversity
- KYC completion
- Platform usage
- Device type

Deliverables:

- Churn segmentation
- Churn prediction model
- Feature importance analysis

---

# 11. Product Event Taxonomy (Inferred)

## Lifecycle Events

- signup_completed
- kyc_completed
- first_transaction_success
- second_transaction_success
- repeat_transaction
- churn_risk_detected

## Transaction Events

- payment_success
- payment_failed
- merchant_expansion
- high_value_transaction

## Behavioral Events

- power_user_unlocked
- category_expansion
- retention_milestone

---

# 12. North Star Metrics

- Monthly Active Transacting Users (MATU)
- Transactions per Active User
- First-Week Activation Rate
- 30-Day Retention Rate
- Funnel Conversion Rate
- Churn Rate
- Power User Rate

---

# 13. Deliverables

- Cleaned analytical fact table
- SQL metric layer
- Funnel dashboard
- Cohort models
- Retention models
- Churn prediction models
- Segmentation models
- Experimentation analysis
- Event taxonomy framework
- Executive dashboard
- Product KPI dashboard
- Product recommendations
- Portfolio case study
- Interview-ready storytelling deck
