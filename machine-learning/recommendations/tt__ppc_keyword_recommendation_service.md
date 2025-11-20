### PPC Keyword Recommendation Service

## Company 
Tandem Theory 

## Client
Rent-A-Center

## Problem 
Client lacked data-driven keyword recommendation capabilities for PPC campaigns, requiring manual keyword research and bid optimization without leveraging customer lifetime value (CLV) insights or historical campaign performance data to optimize keyword selection and maximum cost-per-click (CPC) bidding across millions in annual ad spend.

## Solution
Developed a PPC keyword recommendation service using Google Ads data (via Google Ads API) and the Customer Analytics 360 (CA360) we built with CLTV capabilities to provide keyword recommendations with maximum PPC bidding strategies. Built machine learning models using AWS SageMaker (XGBoost, gradient boosting) that analyze keyword performance (click-through rates, conversion rates, cost per acquisition), customer acquisition costs, and CLTV to recommend high-value keywords and optimal bid strategies.

Implemented automated workflows using Airflow that aggregate Google Ads performance data (impressions, clicks, conversions, spend) and integrate with CA360 customer data via BigQuery to calculate customer lifetime value and return on ad spend (ROAS) by keyword. The service provides keyword recommendations ranked by CLTV-adjusted performance metrics (CLTV/CAC ratios, expected lifetime value per keyword), enabling budget allocation toward keywords that drive higher lifetime value customers with ROI-based prioritization.

All keyword recommendations include maximum CPC suggestions based on CLTV calculations, expected conversion rates from historical data (2+ years), and performance predictions from machine learning models, with automated scoring and ranking updated weekly via Airflow DAGs. The system processes 1000s of keywords and recommends top performers with confidence scores.

## Technology
- Google Analytics 360
- Google Ads API
- Airflow
- AWS (Amazon Web Services)
- SageMaker (XGBoost)
- Python (pandas, scikit-learn)
- BigQuery
- Machine learning models (gradient boosting, classification)
- Customer Analytics 360 (CA360)
- CLTV modeling
- SQL (BigQuery SQL)

## Results
[do not forget to include results of effort here]

_pending: true

