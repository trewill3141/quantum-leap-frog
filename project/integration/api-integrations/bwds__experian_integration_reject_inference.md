### Experian Integration for Reject Inference Analysis

## Company 
BorrowWorks 

## Client
All 5 Portfolios

## Problem 
Client required bidirectional data integration between Snowflake data warehouse and Hive cluster for reject inference analysis with Experian data, but lacked automated framework to move performance data between platforms, resulting in manual data transfers and delayed analysis cycles for data science teams.

## Solution
Architected bidirectional framework enabling data scientists to integrate Snowflake performance data into Hive cluster using Airflow DAGs and sensors, writing data as Parquet files and dynamically generating trigger files for seamless cluster integration. Built automated workflow that handles data egress from Snowflake, transformation to Parquet format, and ingress into Hive cluster with complete orchestration and monitoring.

Developed reverse integration where Hive tables stored as ORC format are built as external Snowflake tables in S3, enabling data science teams to query Experian data directly from Snowflake while maintaining data in Hive for distributed processing. Implemented external table definitions in Snowflake that reference S3 locations containing Hive ORC files, enabling cross-platform data access.

Built comprehensive monitoring and alerting system reporting all egress/ingress operations and build steps into Slack for primary users and analyst review. Implemented Airflow sensors to detect file readiness and trigger downstream processes, ensuring reliable data pipeline execution with automatic retry logic and failure notifications.

All data movement operations include data validation, schema reconciliation, and audit logging to ensure data integrity across platforms. The framework supports both scheduled batch operations and on-demand data transfers based on analysis requirements.

## Technology
- Hive
- AWS (S3)
- Airflow (DAGs, sensors)
- Snowflake
- dbt
- Slack (API integrations)
- Parquet file format
- ORC file format
- Python
- SQL

## Results
[do not forget to include results of effort here]

_pending: true

