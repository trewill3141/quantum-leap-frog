### Funnel Model - Page Views to Payments

## Company 
Bity 

## Client
Bitly

## Problem 
Client lacked comprehensive funnel analysis capabilities to track customer journey from initial page views through to payment conversions, preventing visibility into conversion drop-offs and optimization opportunities across the full customer lifecycle, including millions of monthly events.

## Solution
Developed end-to-end funnel model using Snowplow for event tracking (web, mobile, API events) and transactional database signals (PostgreSQL) to capture customer journey from page views to payments, creating a full customer 360 view. Built data transformation pipelines using dbt (data build tool) on top of BigQuery to model funnel stages and conversion metrics with standardized definitions.

Implemented funnel stage definitions (awareness, interest, consideration, purchase, retention) with event attribution and customer journey mapping using session reconstruction logic. The model tracks user interactions across web properties (page views, clicks, form submissions), feature usage (link creation, analytics views), engagement metrics (session duration, feature adoption), and transactional events (subscription signups, payments) to provide complete visibility into conversion funnel performance.

All funnel data is transformed and modeled in BigQuery using dbt for version control and modular SQL, enabling self-service analytics and dashboard creation for stakeholders via Looker/Data Studio with funnel visualization capabilities.

## Technology
- Snowplow (event tracking)
- Transactional database signals (PostgreSQL)
- dbt (data build tool)
- BigQuery
- SQL (BigQuery SQL)
- Python (pandas)
- Event tracking
- Customer journey analytics
- Looker/Data Studio

## Results
[do not forget to include results of effort here]

_pending: true

