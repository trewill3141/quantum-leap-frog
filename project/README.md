# Project Documentation

This directory contains detailed project documentation organized by technical domain and function.

## Directory Structure

```
project/
├── analytics/                    # Analytics and reporting projects
│   ├── customer-analytics/       # Customer 360, funnel models, MRR models
│   ├── attribution/              # Attribution modeling projects
│   └── reporting/                # Reporting platforms, dashboards, BI environments
├── infrastructure/               # Data infrastructure and modeling projects
│   ├── warehouse-management/     # Warehouse scaling, optimization, disaster recovery
│   └── data-modeling/            # Data modeling, schemas, unified models
├── machine-learning/             # ML and predictive analytics projects
│   ├── recommendations/          # Recommendation engines, keyword models, product models
│   └── forecasting/              # Forecasting models, ad spend predictions
├── integration/                  # Data integration and migration projects
│   ├── migrations/               # Platform migrations, system transitions
│   └── api-integrations/         # API integrations, external data connections
└── monitoring/                   # Monitoring and alerting projects
    └── alerting/                 # Fraud detection, metric monitoring, alerting systems
```

## File Naming Convention

Project files follow a consistent naming pattern:
- **Format**: `{company_prefix}__{project_name}.md`
- **Company Prefixes**:
  - `bwds__` - BorrowWorks
  - `tt__` - Tandem Theory
  - `dwp__` - Dream World Partners
  - `bt__` or `btly__` - Bitly
  - `ag__` - Algo
  - `ewc__` - European Wax Center (client-specific)

## Project File Structure

Each project file contains:
- **Company**: The consulting/employer company
- **Client**: The client company (if applicable)
- **Problem**: The business/technical problem being solved
- **Solution**: The approach and implementation details
- **Technology**: Technologies, tools, and frameworks used
- **Results**: Outcomes and impact (when available)
- **Status**: `_pending: true` flag indicates documentation needs refinement

## Quick Reference

### Analytics Projects
- **Customer Analytics**: Customer Analytics 360 implementations, funnel models, MRR tracking
- **Attribution**: Multi-touch attribution models, marketing attribution analysis
- **Reporting**: Digital reporting platforms, Looker environments, BI implementations

### Infrastructure Projects
- **Warehouse Management**: Snowflake optimization, incremental processing, disaster recovery, warehouse scaling
- **Data Modeling**: Dimensional modeling, star schemas, unified data models, data architecture

### Machine Learning Projects
- **Recommendations**: PPC keyword recommendations, product recommendation models, personalized recommendations
- **Forecasting**: Ad spend forecasting, revenue forecasting, time series predictions

### Integration Projects
- **Migrations**: Adobe to GA360, ADP to Workday, platform transitions
- **API Integrations**: Experian integration, affiliate software, digital tagging, webhook integrations

### Monitoring Projects
- **Alerting**: Fraud detection pipelines, metric monitoring services, automated alerting systems

## Overview

For a high-level overview of all projects, see [projects.md](./projects.md).

