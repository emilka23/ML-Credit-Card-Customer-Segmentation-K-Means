# Credit Card Customer Segmentation

## Project Overview
This project applies **Unsupervised Machine Learning** to segment a credit card customer base. By identifying distinct behavioral and financial patterns, the model provides a data-driven foundation for personalized marketing strategies and risk management. 

The analysis successfully identifies **five distinct customer personas** based on transaction history, income levels, and credit utilization.

##  Tech Stack
* **Language:** Python 
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Algorithm:** K-Means Clustering
* **Dimensionality Reduction:** Principal Component Analysis (PCA)

## Identified Customer Personas
* **Cluster 1 (Power Engines):** High-income, high-frequency transactors.
* **Cluster 2 (Wealthy Convenience):** High-net-worth individuals with low credit utilization.
* **Cluster 3 (Household Managers):** Married female segment with high reliance on credit lines.
* **Cluster 4 (Stable Neutrals):** Average income and spending habits with unknown demographic data.
* **Cluster 5 (Independent Starters):** High-utilization, single/divorced female segment.

## 💡 Key Data-Driven Insights
* **Revenue Growth:** Targeted activation programs for Cluster 2 (high income/low use) can increase card primary usage.
* **Risk Mitigation:** Close monitoring of Cluster 3 and 5 is recommended due to high utilization ratios (up to 37%).
* **Data Strategy:** Identified a significant gap in marital status data for Cluster 4, suggesting a need for improved data collection at onboarding.

Dataset : https://raw.githubusercontent.com/moscmh/creditcard/main/customer_segmentation.csv
