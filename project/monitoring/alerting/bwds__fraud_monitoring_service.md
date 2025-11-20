### Fraud Monitoring Service

## Company 
BorrowWorks 

## Problem 
Fintech company responsible for underwriting and fraud identification of lending platforms lacked real-time, actionable fraud monitoring capabilities, resulting in delayed detection and response to fraudulent activities.

## Solution
Architected an automated fraud detection pipeline using Qlik EM to replicate key tables to Snowflake, executing SQL via Airflow to calculate fraud propensity scores across applications. The system layers multiple fraud signals and key identifiers from fraud monitoring tools integrated into the application process.

When exception criteria are met based on signals and propensity scores, the system triggers PagerDuty alerts and Slack notifications containing investigative Snowflake queries and the top 10 fraudulent applications, enabling immediate action by the fraud team.

All events and calculations are logged in Snowflake for post-mortem analysis and model refinement.

## Technology
- Airflow 
- Snowflake 
- Slack 
- PagerDuty 
- Qlik EM

## Results
Increased fraud visibility from next-day detection to within 2 hours, enabling the identification of 2 fraud rings before they progressed beyond the second hour of fraudulent activity. Reduced time-to-underwriting changes by providing real-time fraud signals, significantly mitigating bad debt and revenue impact. 