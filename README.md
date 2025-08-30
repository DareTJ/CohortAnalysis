# Cohort Analysis

This project analyses **customer retention in e-commerce** using **Cohort Analysis** and **RFM Segmentation**. The goal is to uncover retention trends, segment customers into meaningful groups and generate **actionable insights** to improve customer loyalty and reduce churn

**Dataset**

1. **Raw dataset**: Dataset_ecommerce.csv,
2. **Cleaned dataset**: Dataset_ecommerce_cleaned.csv,
3. **With Cohort Index**: Dataset_ecommerce_with_cohort_index.csv,
4. **Retention Matrix**: Cohort_Retention_Matrix.csv

Key fields include: InvoiceNo, InvoiceDate, CustomerID, Quantity, UnitPrice, Country.

**Project Workflow**

1.  **Data Cleaning & Preprocessing**
     - Removed missing IDs
     - Extracted InvoiceMonth & CohortMonth
     - Computed CohortIndex(months since first purchase)

2. **Cohort Analysis**
     - Built cohort retention matrices
     - Visualised retention with heatmap

3. **RFM Segmentation & Clustering**
    - Engineered Recency, Frequency, Monetary features
    - Applied KMeans clustering to identify customer groups

4. Insights & Recommendations
   - First-month drop-off is high -> improve onboarding & early engagement
   - High value customers drive majority of revenue -> nurture with VIP perks
   - At-risk customers -> reactivation campaigns
   - One-time buyers -> targeted offers to encourage repeat purchases
  
**Visualizations**
   - Retention heatmap(by cohorts)
   - RFM clustering profile
