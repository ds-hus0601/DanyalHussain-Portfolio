# 👥 Customer Segmentation with Clustering

> 🧩 This project was completed as part of the **University of Cambridge Data Science & Machine Learning Career Accelerator (2025)**.  
> It applies unsupervised learning to segment customers based on spending and engagement behaviours.

---

### Objective
To identify distinct customer groups using unsupervised clustering methods, enabling data-driven marketing strategies and personalised engagement.  
The dataset simulates transactional records, including spending frequency, recency, and monetary value metrics.

---

### Approach
- Performed **data cleaning and standardisation** to prepare numeric features for clustering.  
- Applied **feature engineering** to derive Recency–Frequency–Monetary (RFM) and cost-based metrics.  
- Trained multiple clustering algorithms to explore segmentation patterns:
  - **K-Means Clustering**
  - **Hierarchical (Agglomerative) Clustering**
  - **DBSCAN (Density-Based Spatial Clustering)**
- Used **Elbow Method** and **Silhouette Score** to determine optimal cluster count.  
- Visualised separability using **PCA** and **t-SNE**, highlighting distinct behavioural groups.

---

### Tools & Techniques
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
Models: K-Means, Hierarchical Clustering, DBSCAN  
Feature Engineering: RFM metrics, standard scaling  

---

### Results
- Identified **three primary customer clusters** based on recency, frequency, and spending patterns.  
- Cluster profiles revealed clear behavioural differences between high-value, occasional, and inactive customers.  
- Visual analysis confirmed strong separation and interpretability, validating the clustering pipeline.  
- The findings could support **targeted promotions**, **churn prevention**, and **loyalty strategy design**.

---

### Key Learning
This project strengthened understanding of **unsupervised learning, feature scaling, and cluster validation**.  
It demonstrated how clustering techniques can uncover actionable marketing insights and guide decision-making in customer analytics.  

---

🔗 [⬅️ Back to Main Portfolio](../README.md)
