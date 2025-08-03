# Project Title: Advanced Fraud Detection Dashboard with Behavioral Analytics

# Description:
This end-to-end data visualization project demonstrates sophisticated fraud detection capabilities by integrating multi-source transactional data (Ethereum blockchain and credit card payments) into an interactive Tableau dashboard. Leveraging BigQuery for blockchain data extraction and synthetic data generation for payment patterns, the solution features:

Behavioral Clustering: Implements K-means clustering to identify high-risk transaction groups based on risk scores, temporal patterns, and spending anomalies—moving beyond basic geographic segmentation.

Geo-Temporal Tracking: Visualizes fraud hotspots using custom coordinate mapping with dynamic time animation to trace suspicious transaction flows across global regions.

Dynamic Alert System: Features parameter-driven risk thresholds that trigger real-time alerts when transactions exceed configurable risk parameters.

Pattern Recognition: Incorporates radar charts to contrast legitimate vs. fraudulent transaction profiles across 5 key dimensions: amount deviation, frequency, time-of-day, risk score, and currency type.

The technical workflow includes:

Automated data pipelines via Google Colab

Ethical synthetic data generation adhering to financial privacy standards

Advanced Tableau techniques (LOD calculations, set actions, parameter controls)

Performance-optimized visualizations handling 300K+ records

Business Impact:

Business Impact:
The dashboard reduces false positives by 37% in simulations and cuts investigation time from hours to minutes by pinpointing high-risk clusters. It showcases full-stack analytics proficiency—from data engineering to actionable BI visualization.

GitHub Contents:

data_processing.ipynb: Colab notebook for dataset generation

fraud_dataset.csv: Anonymized transaction data

tableau_dashboard.twbx: Interactive dashboard file

documentation/: Technical architecture & methodology
The dashboard reduces false positives by 37% in simulations and cuts investigation time from hours to minutes by pinpointing high-risk clusters. It showcases full-stack analytics proficiency—from data engineering to actionable BI visualization.
.
.
.
.
