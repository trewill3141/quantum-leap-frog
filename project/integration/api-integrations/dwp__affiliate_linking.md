### Affiliate Linking Implementation

## Company 
Dream World Partners 

## Problem 
Client required persistent HREF tracking for affiliate links across website navigation and user journeys, but existing tagging infrastructure did not maintain referrer information through page transitions and redirects.

## Solution
Implemented a GTM-based solution to persist HREF referrer information across page loads and navigation events. Developed custom JavaScript and GTM tag configurations (Custom HTML tags, Data Layer variables) to capture and maintain affiliate link data throughout the user session via first-party cookies.

The solution tracks referrer information in cookies (with 30-day expiration) and URL parameters, ensuring affiliate attribution is maintained even when users navigate through multiple pages or experience redirects. Integration with Google Analytics 360 via Enhanced Ecommerce events enables accurate affiliate performance tracking with conversion attribution.

All affiliate link data is logged in Google Analytics and BigQuery for analysis and attribution modeling, including affiliate partner identification, click-through rates, and conversion attribution.

## Technology
- Google Tag Manager (GTM)
- JavaScript (custom scripts)
- Cookie management (first-party cookies)
- Google Analytics 360
- BigQuery
- Data Layer

## Results
[do not forget to include results of effort here]

_pending: true

