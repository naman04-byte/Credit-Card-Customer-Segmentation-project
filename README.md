# Credit Card Customer Segmentation
Segmented 8,950 credit-card customers into 4 personas using K-Means clustering (k chosen via Elbow method
and Silhouette score 0.21, validated against Hierarchical clustering and DBSCAN). Visualized clusters with
PCA (55.5% variance) and identified a high-risk "cash-advance revolver" segment (1,655 customers, 96% revolving rate).
Saved the StandardScaler + K-Means pipeline (.pkl) to assign segments to new customers automatically.
**Tech:** Python, pandas, scikit-learn, Matplotlib, Seaborn
