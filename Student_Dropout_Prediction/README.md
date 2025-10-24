# 🎓 Student Dropout Prediction (Confidential Education Dataset)

> 🧩 Completed as part of the **University of Cambridge Data Science & Machine Learning Career Accelerator (2025)** using anonymised educational data under confidentiality agreement.  
> This project predicts student dropout risk through staged data modelling, integrating application, engagement, and academic performance datasets.

---

### 🎯 Objective
To develop a predictive model capable of identifying students at risk of dropping out early, enabling proactive academic and wellbeing interventions.  
The dataset covered three key phases of the student lifecycle — **application**, **engagement**, and **academic performance** — replicating a real-world educational setting.

---

### 🧩 Approach
- Cleaned and preprocessed structured data across three progressive stages:  
  **Stage 1** – Application and demographic data  
  **Stage 2** – Engagement and attendance metrics  
  **Stage 3** – Academic performance indicators  
- Engineered features such as attendance frequency, module outcomes, and engagement scores.  
- Built and compared two supervised learning models:  
  - **XGBoost Classifier**  
  - **Neural Network (TensorFlow/Keras)**  
- Applied **grid search** for tuning learning rate, epochs, and batch size.  
- Evaluated models using **Accuracy**, **F1 Score**, and **Recall** to prioritise sensitivity for high-risk detection.  
- Used **feature importance** and **confusion matrices** for interpretation.  
- All data were fully anonymised — no identifiable student or institutional information is included.

---

### 🛠️ Tools & Techniques
**Languages & Libraries:** Python (Pandas, NumPy, Scikit-learn, TensorFlow, Keras, XGBoost, Matplotlib, Seaborn)  
**Methods:** Classification · Feature Engineering · Hyperparameter Tuning · Model Evaluation  
**Metrics:** Accuracy · F1 Score · Recall · Confusion Matrix Analysis  

---

### 📊 Results
- **XGBoost** achieved the highest recall, effectively capturing most at-risk students.  
- **Neural Network** demonstrated strong convergence in later stages once academic features were introduced.  
- **Stage 3 models** delivered near-perfect recall when academic marks and module outcomes were included.  
- Key predictors included engagement frequency, attendance, and average marks.  
- Provided practical insight into how institutions can apply predictive analytics to support retention initiatives.

---

### 🧠 Key Learnings
This project demonstrated how **machine learning supports student retention** by enabling early, data-driven intervention.  
It reinforced expertise in **multi-stage data modelling, feature engineering, and model interpretability** within a confidential educational environment.  

---

🔗 [⬅️ Back to Main Portfolio](../README.md)
