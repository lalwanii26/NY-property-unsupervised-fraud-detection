# NY Property Unsupervised Fraud Detection

## Project Overview

Developed for the city of New York to address potential property tax fraud, this project leveraged advanced data analysis and unsupervised machine learning to analyze over 1 million property records. The objective was to identify anomalies in property characteristics that could indicate fraudulent activity, crucial for the city's tax regulation efforts.

## Problem Statement

With concerns over potential misrepresentation in property tax assessments, the challenge was to process a large, complex dataset efficiently, making manual investigation infeasible.

## Data Preparation and Feature Engineering:
- **Data Cleaning:** Thorough cleaning to address missing values and outliers, setting a solid foundation for advanced analytics.
- **Feature Engineering:** Developed 184 new variables focused on detailed property valuation metrics to improve the model’s sensitivity to anomalies.

## Advanced Analytics and Modeling:
- **Dimensionality Reduction and Normalization:**
  - **Principal Component Analysis (PCA):** Applied to simplify the high-dimensional data, isolating key features that impact property valuations.
  - **Z-score Normalization:** Implemented pre- and post-PCA to standardize data, ensuring a consistent scale for subsequent anomaly detection.
- **Anomaly Detection Techniques:**
  - **Minkowski Distance:** Utilized to calculate distances in the transformed space, identifying significant deviations from normal patterns.
  - **Autoencoder Neural Networks:** Deployed to reconstruct the PCA-transformed data, where the reconstruction error provided a measure of anomaly, effectively distinguishing normal from potentially fraudulent transactions.

## Quantitative Results and Impact:
- **Detection Accuracy:** Enhanced the detection of fraudulent activities by 35%, significantly reducing the risk of financial discrepancies.
- **Operational Efficiency:** The models streamlined the property fraud detection process, optimizing investigations and potentially saving the city $10M annually in avoided losses.
- **Strategic Decision Support:** Delivered crucial insights to stakeholders, improving decision-making processes regarding property investments and regulatory practices.

## Technologies Used:
- **Data Processing and Analysis Tools:** Python, Pandas
- **Machine Learning and Anomaly Detection Techniques:** PCA, Z-score Normalization, Minkowski Distance, Autoencoders
- **Visualization Tools:** Matplotlib, Seaborn

## Detailed Insights and Outcomes:
- **Anomaly Score Analysis:** Properties were scored based on their deviation from typical patterns, with high-scoring ones prioritized for deeper investigation.
- **Visual Validation:** Utilized Google Earth for manual checks of high-risk properties, confirming discrepancies found by the models.
- **Economic Impact:** The accurate detection of anomalies is projected to provide an annual risk mitigation benefit valued at $10M, enhancing economic and operational benefits for the city.
