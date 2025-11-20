### Unified Models - Bitly and QRCP Integration

## Company 
Bity 

## Client
Bitly/QRCP

## Problem 
Bitly acquired a QR code company (QRCP) a year before project initiation and needed to analyze data at a higher level across both platforms, but lacked unified data models that could accommodate both source system specificity and unified data simplicity for cross-platform analytics across millions of daily events.

## Solution
Architected a dual-model approach using source system models (staging layer) and common unified models (marts layer) built with dbt on BigQuery. Developed source system-specific models that preserve platform-specific data structures and business logic from both Bitly (link analytics, click tracking) and QRCP (QR code generation, scan tracking), enabling detailed platform-specific analysis with 50+ source models.

Built unified common models (20+ unified models) that harmonize data structures across both platforms, enabling cross-platform analytics and reporting (customer journey, engagement metrics, revenue attribution) while maintaining the ability to drill down into source system specifics when needed via dimension flags. The architecture allows for both granular platform-specific insights and high-level unified business metrics.

All models are version-controlled using dbt with modular SQL transformations (macros, tests, documentation), enabling efficient maintenance and updates as both platforms evolve with automated testing and data quality checks.

## Technology
- BigQuery
- dbt (data build tool)
- SQL (BigQuery SQL)
- Python (pandas)
- Data modeling (staging and marts layers)
- ETL pipelines
- Git (version control)

## Results
[do not forget to include results of effort here]

_pending: true

