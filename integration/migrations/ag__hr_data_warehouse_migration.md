### HR Data Warehouse Migration from ADP to Workday

## Company 
Algo 

## Client
Driven Brands

## Problem 
Client required migration of HR data warehouse from ADP to Workday while maintaining existing data products, pipelines, and tools that depend on HR data across multiple business units, necessitating a seamless transition with backward compatibility to avoid disrupting downstream analytics and reporting for 100+ dependent dashboards and reports.

## Solution
Architected and executed migration of HR data warehouse from ADP to Workday by integrating both source systems into GCP, enabling parallel operation during transition period (3-month migration window). Developed common data models using dbt that abstracted both ADP and Workday data sources, maintaining backward compatibility to ensure existing data products, pipelines, and tools continued to operate without modification.

Built ETL pipelines using Airflow and Python to extract data from both ADP (via API) and Workday (via Workday API/RaaS) systems, transforming and loading into BigQuery with standardized schemas. Implemented data mapping and transformation logic to harmonize data structures between systems (employee records, payroll, benefits, time tracking, organizational hierarchy) while preserving data lineage and quality with automated reconciliation processes.

All data models include data validation and reconciliation processes (row count comparisons, field-level validation, referential integrity checks) to ensure accuracy and completeness across both source systems during the migration window, with <0.5% variance between systems.

## Technology
- ADP (API integration)
- Workday (RaaS API)
- GCP (Google Cloud Platform)
- Airflow
- BigQuery
- Python (pandas)
- dbt (data build tool)
- SQL (BigQuery SQL)
- ETL pipelines

## Results
[do not forget to include results of effort here]

_pending: true

