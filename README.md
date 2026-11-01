# E-Commerce Customer Segmentation

## Project Overview
This project focuses on segmenting e-commerce customers using RFM (Recency, Frequency, Monetary) analysis and unsupervised machine learning algorithms.

The objective is to identify different customer groups and develop actionable marketing strategies.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Workflow
1. Data loading and preprocessing
2. Data cleaning and handling missing values
3. RFM feature engineering
4. Log transformation and feature scaling
5. K-Means clustering
6. DBSCAN clustering
7. PCA dimensionality reduction
8. t-SNE visualization
9. Customer profiling and marketing personas

## Algorithms and Results

| Technique | Result |
|---|---|
| K-Means | 2 clusters |
| Best Silhouette Score | 0.4328 |
| DBSCAN | 2 clusters + 62 noise points |
| PCA | 93.87% variance retained |
| t-SNE | 2D visualization |

## Customer Segments

### 1. High-Value Customers
- 1,666 customers
- Average Recency: 25.89 days
- Average Frequency: 8.44
- Average Monetary: 4,539.60

**Marketing Strategy:** VIP rewards, loyalty programmes and exclusive offers.

### 2. Low-Engagement Customers
- 2,672 customers
- Average Recency: 134.09 days
- Average Frequency: 1.67
- Average Monetary: 495.59

**Marketing Strategy:** Win-back campaigns, personalized discounts and reminders.

## Project Files
- `Ecommerce_Customer_Segmentation.ipynb` — Complete analysis and implementation.
- `README.md` — Project documentation.



## Conclusion
The project demonstrates how RFM analysis and clustering algorithms can help identify customer segments and support data-driven marketing decisions.
