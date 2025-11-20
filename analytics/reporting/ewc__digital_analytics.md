### Digital Analytics Environment

## Company 
Tandem Theory 

## Client
European Wax Center

## Problem 
Personal services brand migrating from brick-and-mortar franchise model to digital model with GA360 and BigQuery, but lacked technical resources and architecture to leverage these components effectively for analytics and reporting.

## Solution
Architected a Kimball/medallion-style analytical model set that enables comprehensive digital analytics on top of GA360 and BigQuery. Designed dimensional data models with star schema structures (fact tables for events/sessions, dimension tables for dates, users, products, campaigns) optimized for analytics and reporting use cases.

Built ETL pipelines using Python and Airflow to transform raw GA360 data (daily exports from GA360 to BigQuery) into structured analytical models in the medallion architecture: bronze (raw data), silver (cleaned/standardized), and gold (business-ready aggregates) layers. Each layer ensures data quality validation and transformation, enabling self-service analytics and supporting various business intelligence use cases via Looker.

All analytical models (20+ fact tables, 15+ dimension tables) are documented with data dictionaries and business logic definitions in Confluence/wiki.

## Technology
- Google Analytics 360
- BigQuery
- SQL (BigQuery SQL)
- Python (pandas)
- Airflow
- Looker
- Dimensional modeling (Kimball methodology)
- ETL pipelines

## Results
[do not forget to include results of effort here]

_pending: true
