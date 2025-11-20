### Adobe Analytics to GA360 Migration

## Company 
Tandem Theory 

## Client
Rent-A-Center

## Problem 
Client required migration from Adobe Analytics to GA360 + BigQuery, necessitating functional replacement of Adobe's flat file export for sessions and events with sessionization and business logic application in a new analytics infrastructure, while maintaining reporting parity for 50+ existing reports.

## Solution
Architected analytics infrastructure to functionally replace Adobe Analytics export capabilities with GA360 + BigQuery implementation. Developed custom sessionization logic using SQL (based on 30-minute inactivity timeout and midnight reset) and business rules to replicate Adobe's data structure and reporting capabilities while leveraging BigQuery's scalability for processing billions of events.

Built data pipelines using Python and Airflow to migrate 2+ years of historical data (billions of rows) and established ongoing data collection processes via GA360 export to BigQuery. Implemented event tracking via GTM and session reconstruction using BigQuery SQL to match Adobe Analytics data models (visit number, visit depth, time on site), enabling seamless transition for reporting and analysis.

All migrated data includes data quality validation and reconciliation processes (row count comparisons, metric validation) to ensure accuracy with less than 1% variance from source data.

## Technology
- Google Analytics 360
- BigQuery
- SQL (BigQuery SQL)
- Python
- Airflow
- Google Tag Manager
- ETL pipelines
- Sessionization logic

## Results
[do not forget to include results of effort here]

_pending: true

