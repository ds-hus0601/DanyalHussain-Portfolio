# 🎓 Student Dropout Prediction (Confidential Education Dataset)

> 🧩 This project was completed as part of the **University of Cambridge Data Science & Machine Learning Career Accelerator (2025)** using an anonymised education dataset under a confidentiality agreement.  
> It focuses on predicting student dropout risk through staged data modelling, integrating application, engagement, and performance data.

---

### Objective
To develop a predictive model capable of identifying students at risk of dropping out early, enabling proactive support strategies.  
The dataset covered three phases of student data — **application, engagement, and academic performance** — representing a real-world educational context.

---

### Approach
- Cleaned and preprocessed structured data from multiple stages (application → engagement → performance).  
- Engineered features representing attendance, coursework completion, and engagement frequency.  
- Trained and compared two supervised models:
  - **XGBoost Classifier**
  - **Neural Network (TensorFlow)**
- Tuned hyperparameters (learning rate, epochs, batch size) using **grid search** and cross-validation.  
- Evaluated models using **Accuracy**, **F1 Score**, and **Recall** to balance prediction sensitivity with reliability.  
- Interpreted results through feature importance plots and confusion matrices to highlight key predictors of risk.  
- All records were fully anonymised, with no identifiable student or institutional data disclosed.

---

### Tools & Techniques
Python (Pandas, NumPy, Scikit-learn, TensorFlow, XGBoost, Matplotlib, Seaborn)  
Machine Learning: Classification, Feature Engineering, Hyperparameter Optimisation  
Metrics: Accuracy, F1 Score, Recall, Confusion Matrix Analysis  

---

### Results
- The **XGBoost model** achieved the highest recall, making it more effective for early-risk detection.  
- Identified key features linked to dropout, including engagement frequency and academic performance consistency.  
- Produced clear model evaluation visuals and an interpretable feature ranking.  
- Delivered practical insight into how educational institutions could use data-driven early interventions.

---

### Key Learning
This project demonstrated how **predictive analytics can support student retention strategies** by identifying risk early.  
It also reinforced advanced skills in **model tuning, evaluation, and interpretability** within confidential data environments.  
