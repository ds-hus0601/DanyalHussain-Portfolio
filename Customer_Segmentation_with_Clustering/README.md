# 🧩 Customer Segmentation with Clustering

### Objective  
Segment e-commerce customers based on purchasing patterns to identify valuable groups for targeted marketing and retention strategies.

### Overview  
This project applied unsupervised learning techniques to cluster customers using key behavioral and transactional features. By grouping customers according to Recency, Frequency, Monetary value (RFM), and unit cost, the analysis helped reveal distinct patterns in purchase behavior.

### Approach  
- Cleaned and preprocessed transactional data for missing values and scaling.  
- Engineered RFM features and calculated total spend per customer.  
- Applied **K-Means** and **Hierarchical Clustering** to identify customer segments.  
- Used **PCA** and **t-SNE** to visualise the separability of clusters.  
- Compared silhouette scores to determine optimal cluster numbers.

### Tools & Libraries  
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
Jupyter Notebook for analysis and visualisation.

### Results  
- Identified 3–4 meaningful customer groups (e.g., high-value, frequent, and at-risk customers).  
- Highlighted differences in spending frequency and recency that can guide loyalty campaigns.  
- Demonstrated how unsupervised models can drive segmentation for targeted marketing strategies.

### Key Learnings  
This project reinforced the importance of **feature scaling**, **cluster validation**, and **visualisation** in understanding customer heterogeneity.  
It also illustrated the link between statistical clustering and actionable business decisions.
