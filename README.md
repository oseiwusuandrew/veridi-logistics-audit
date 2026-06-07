# Veridi Logistics Delivery Performance Audit

## Executive Summary
This project analyzes delivery performance for Veridi Logistics using the Olist e-commerce dataset. The goal is to determine whether inaccurate delivery estimates and logistics delays are impacting customer satisfaction.

Findings show that while 93.23% of deliveries are completed on time, late deliveries significantly reduce customer satisfaction. There is also clear regional variation in delivery performance, indicating that logistics inefficiencies are not uniform across all states.

## Project Links
- Dashboard: https://public.tableau.com/views/VeridiLogisticsDeliveryPerformanceAudit_17808699242500/VeridiLogisticsDeliveryPerformanceAudit?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
- Notebook: https://colab.research.google.com/drive/1BbZ4XWxqE1x_7Diwdr6i24HrO8zQWcIQ?usp=sharing
## Data Cleaning & Preparation
- Merged Orders, Customers, Reviews, and Products datasets into a master dataset
- Converted date fields to proper datetime format
- Created delivery delay metric (days_difference)
- Classified deliveries into On Time, Late, and Super Late
- Handled missing and incomplete delivery records

## Key Insights
- 93.23% of deliveries are on time
- Late deliveries significantly reduce customer review scores
- Certain states experience higher delay rates than others
- Delivery delays are negatively correlated with customer satisfaction (-0.27)

## Candidate’s Choice Analysis
An additional analysis was conducted on product categories to determine whether certain types of products are more prone to delivery delays. Results show that bulky and complex items such as furniture and home goods have higher delay rates, suggesting the need for category-specific logistics optimization.

## Recommendations
- Improve logistics efficiency in high-delay regions
- Prioritize delivery optimization for high-risk product categories
- Align estimated delivery dates more accurately with real delivery performance
