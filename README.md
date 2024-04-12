# NY Property Unsupervised Fraud Detection

## Overview
This project aims to develop an algorithm to detect potential tax fraud within New York City's property records. With over 1 million records and 32 fields, the city lacks the resources to manually scrutinize each entry for irregularities. The objective is to build a machine learning model capable of identifying anomalies in property data that may indicate fraudulent activity, specifically focusing on instances where property values deviate significantly from expected norms.

## Problem Statement
The city of New York suspects the presence of property tax fraud but lacks a systematic approach to uncover it. The data is extensive, messy, and contains numerous missing values. The task is to develop an algorithm that can analyze the dataset to pinpoint records with unusual property characteristics, potentially indicating underreported tax values.

## Approach
1. **Data Exploration**: Analyze the dataset to understand its structure, identify missing values, and explore the distribution of property characteristics.
2. **Unsupervised Learning**: Utilize unsupervised learning techniques, particularly k-means clustering, to identify clusters of similar records based on property characteristics.
3. **Anomaly Detection**: Identify records that fall outside the norm within their respective clusters, indicating potential fraud.
4. **Fraud Investigation**: Flag the most unusual records for manual investigation by city officials to determine the presence of fraud.

## Outcome
By implementing the ML-driven fraud detection initiative, the project aims to improve anomaly detection by 25% in the dataset, contributing to more effective investment strategies and reduced fraud risks for the city. The estimated annual risk mitigation benefit is valued at $10 million.

## Technologies Used
- Python
- Scikit-learn (for machine learning algorithms)
- Pandas (for data manipulation)
- Matplotlib and Seaborn (for data visualization)

## Impact
The implementation of the fraud detection algorithm is expected to streamline the detection process, enabling city officials to focus their resources on investigating suspicious property records efficiently. This proactive approach not only safeguards against potential revenue losses due to tax fraud but also enhances the overall integrity of the property tax system within New York City.
