### Snowflake Warehouse Disaster Recovery & Rebuild

## Company 
BorrowWorks 

## Client
All 5 Portfolios

## Problem 
Client lacked automated disaster recovery capabilities for Snowflake data warehouse, requiring manual rebuild processes that could take days or weeks to restore operations in case of catastrophic failure. Manual processes were error-prone, lacked documentation, and created significant business continuity risk for fintech lending operations processing billions of transactions daily across 5 portfolios.

## Solution
Architected and implemented automated disaster recovery solution using bash scripts, S3, and Pulumi (Infrastructure as Code) to enable complete warehouse rebuild in hours rather than days or weeks. Built comprehensive automation that recreates entire Snowflake warehouse infrastructure including databases, schemas, warehouses, roles, users, and permissions (RBAC) from code-defined state.

Developed Pulumi-based infrastructure definitions capturing all Snowflake objects and configurations, enabling version-controlled infrastructure management. Created bash scripting layer orchestrating disaster recovery workflow including warehouse shutdown, object recreation from Pulumi definitions, data reload from S3 staging areas, and validation processes ensuring data integrity.

Implemented automated validation and testing procedures that verify warehouse rebuild completeness and data accuracy before declaring recovery complete. The solution includes documentation and runbooks for operational teams to execute disaster recovery procedures.

All infrastructure definitions are version-controlled in Git, and the disaster recovery process is tested regularly to ensure reliability and minimize recovery time objective (RTO).

## Technology
- Pulumi (Infrastructure as Code)
- Bash scripting
- AWS S3
- Snowflake
- Git (version control)
- Infrastructure automation
- RBAC (Role-Based Access Control)

## Results
[do not forget to include results of effort here]

_pending: true

