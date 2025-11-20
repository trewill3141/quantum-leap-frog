### Monthly Recurring Revenue (MRR) Model

## Company 
Bity 

## Client
Bitly/QRCG

## Problem 
Client required a monthly recurring revenue (MRR) model to track and forecast revenue in advance of achieving a $100M MRR goal, but lacked standardized MRR calculation methodology and reporting infrastructure to monitor progress toward this milestone across multiple product lines and customer segments.

## Solution
Developed comprehensive MRR model using dbt on BigQuery to calculate monthly recurring revenue with standardized definitions and methodologies following SaaS industry best practices (new MRR, expansion MRR, contraction MRR, churned MRR, reactivation MRR). Built data transformation pipelines using SQL and Python that aggregate subscription data, billing events, and contract changes to compute MRR components accurately with daily snapshots and monthly rollups.

Implemented MRR trend analysis (MoM growth, YoY growth), cohort analysis (cohort-based retention and expansion), and forecasting capabilities (time series forecasting using Prophet/ARIMA) to track progress toward $100M MRR goal. The model provides detailed breakdowns by customer segment (enterprise, SMB, self-service), product (Bitly, QRCP), and geography (regional MRR), enabling strategic insights for revenue growth initiatives.

All MRR calculations are automated via Airflow DAGs and refreshed monthly (with daily incremental updates), with data validation and reconciliation processes (revenue recognition validation, contract reconciliation) to ensure accuracy and consistency across reporting platforms with <1% variance from finance systems.

## Technology
- BigQuery
- dbt (data build tool)
- SQL (BigQuery SQL)
- Python (pandas, Prophet)
- Airflow
- Revenue analytics
- Financial modeling
- Time series forecasting

## Results
[do not forget to include results of effort here]

_pending: true

