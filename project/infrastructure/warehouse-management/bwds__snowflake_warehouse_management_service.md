### Snowflake Warehouse Management Service

## Company 
BorrowWorks 

## Problem 
Fintech company replicating 3K tables via full-time CDC using Qlik EM with a 500GB disk in AWS. One of 30+ replication tasks occasionally writes 400GB in an hour period 3x per week during morning hours, while 4 other tasks frequently experience high volumes throughout the day as they replicate lending platform data into Snowflake. Given a 15-minute SLA for the data science team, the easiest solution was to manually scale the warehouse to clear backlogs, but doing so manually consumed development time, while leaving it vertically scaled all day (XS to M) resulted in significantly increased costs.

## Solution
Developed an automated Airflow DAG that monitors replication lag in Snowflake and dynamically scales the warehouse horizontally when lag exceeds 15 minutes, and vertically (XS to XL) when lag exceeds an hour. A hysteresis period is maintained so that replication lag must remain below 15 minutes to scale back down to XS, preventing thrashing from rapid scale up/down cycles.

All scaling actions are logged in Snowflake with detailed metrics, and Slack notifications are sent regarding each change executed, providing full visibility into warehouse scaling decisions and cost optimization.

## Technology
- Airflow 
- Snowflake 
- Slack 
- Qlik EM

## Results
Eliminated manual scaling overhead, increased visibility into processing bottlenecks, and reduced time spent reviewing tasks. Achieved projected savings of $100K annually on Snowflake processing costs while maintaining 15-minute SLA compliance.
