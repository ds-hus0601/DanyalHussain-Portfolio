# ⚙️ Ship Engine Anomaly Detection

> 🧩 This project was developed as part of the **University of Cambridge Data Science & Machine Learning Career Accelerator (2025)**.  
> It applies unsupervised learning to detect abnormal operational behaviour in maritime engine sensor data.

---

### Objective
To identify anomalous engine conditions using unsupervised learning methods, providing early alerts for potential system failures and maintenance issues.  
The dataset represents multivariate sensor readings from a ship engine recorded under normal and abnormal conditions.

---

### Approach
- Conducted **data preprocessing and standardisation** to remove noise and scale sensor features.  
- Applied **Principal Component Analysis (PCA)** for dimensionality reduction and visualisation of sensor variance.  
- Trained three unsupervised models:
  - **Isolation Forest**
  - **One-Class SVM**
  - **PCA-based anomaly reconstruction**
- Compared model performance using contamination thresholds, outlier counts, and visual inspection of predicted anomalies.  
- Visualised reconstruction errors and model decision boundaries to interpret anomaly distribution.

---

### Tools & Techniques
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
Models: PCA, Isolation Forest, One-Class SVM  

---

### Results
- PCA effectively reduced noise and improved interpretability of anomaly patterns.  
- Isolation Forest showed robust detection of subtle deviations, outperforming One-Class SVM in sensitivity.  
- The models identified distinct anomaly clusters corresponding to early warning signals of potential malfunction.  
- The workflow was later integrated into an automated Power BI dashboard for ongoing anomaly monitoring.

---

### Key Learning
This project reinforced practical skills in **unsupervised learning and model evaluation for rare-event detection**.  
It demonstrated how combining PCA with tree-based and boundary-based anomaly detectors can uncover system faults without labelled data.  
The results showcase how data-driven maintenance systems can significantly enhance **predictive reliability and operational safety**.
