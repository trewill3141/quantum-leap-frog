### Metric Guard Monitoring Service

## Company 
BorrowWorks 

## Client
All 5 Portfolios

## Problem 
Marketing inefficiencies due to mismanagement were going unnoticed for days, creating significant financial impact before issues were discovered. Lack of real-time monitoring and alerting for key business metrics meant that data quality issues, campaign performance degradation, and operational anomalies were only identified through manual reporting reviews, resulting in delayed response times and missed optimization opportunities.

## Solution
Architected and built Metric Guard monitoring service that automatically queries Snowflake, calculates deltas comparing current metrics vs. previous N days (configurable lookback periods), and routes intelligent Slack messaging to responsible parties, specific Slack channels, and PagerDuty services based on threshold violations and anomaly detection in live data.

Developed dbt macro-based source model architecture that allows engineering teams to declaratively list key parameters (metric name, threshold, lookback period, alert recipients, severity levels) which are automatically translated into rows within the Metric Guard source model. This design enables engineers to add new metrics for monitoring without modifying core monitoring logic, promoting self-service metric management.

Built Airflow DAGs that execute metric validation queries on scheduled intervals (hourly, daily, or custom cadences), compare current values against historical baselines using statistical methods (standard deviation, moving averages), and trigger appropriate alerting workflows based on severity and metric type. The system supports multiple alert channels including Slack direct messages, Slack channels, and PagerDuty escalation policies.

All metric definitions are version-controlled via dbt, ensuring metric monitoring configurations are auditable and maintainable. The service includes alerting logic that prevents alert fatigue through intelligent routing and severity-based escalation.

## Technology
- Snowflake
- dbt (data build tool)
- Airflow
- Slack (API integrations)
- PagerDuty (API integrations)
- SQL (Snowflake SQL)
- Python (alerting scripts)
- dbt macros

## Results
[do not forget to include results of effort here]

_pending: true

