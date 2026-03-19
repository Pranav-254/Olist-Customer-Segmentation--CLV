# Olist-Customer-Segmentation--CLV
This project addresses a critical e-commerce challenge: How do we identify our most valuable customers and predict who is about to leave? Using the Olist Brazilian E-Commerce dataset, I developed a master's level end-to-end pipeline that moves from raw transaction logs to probabilistic future value forecasting and AI-driven customer clustering.

The Tech Stack
Language: Python (Pandas, NumPy)

Probabilistic Modeling: lifetimes (BG/NBD & Gamma-Gamma Models)

Machine Learning: Scikit-learn (K-Means Clustering)

Business Intelligence: Power BI (DAX, Geospatial Heatmaps, Interactive Slicers)

## Key Data Science Implementations
1. Predictive CLV Modeling
Instead of looking only at historical spend, I implemented two advanced probabilistic models:
BG/NBD Model: To predict the expected number of future transactions for each customer.
Gamma-Gamma Model: To estimate the expected average order value.
Result: A 12-month Customer Lifetime Value (CLV) forecast at the individual user level.

2. K-Means Customer Segmentation
I applied K-Means clustering to RFM (Recency, Frequency, Monetary) data and predicted CLV to categorize the user base into four actionable segments:
 Champions: High-value, loyal, and recent shoppers.
 At-Risk: High-value customers who haven't shopped in a long time (Churn candidates).
 Potential Loyalists: New customers with high predicted growth potential.
 Hibernating: Low-value, infrequent shoppers.
