# 🏦 Bank of England – Financial Sentiment & Prudential Metrics

> 🧩 This project was completed as part of a group during the **University of Cambridge Data Science & Machine Learning Career Accelerator (2025)**.  
> The materials here reflect my individual contribution to the analysis and visualisation components.

### Objective
Analyse earnings call transcripts from major UK banks using Natural Language Processing (NLP) to measure sentiment and relate managerial tone to prudential metrics such as CET1, NSFR, LCR, and LDR.  
The goal was to identify whether executive communication tone aligned with financial stability indicators.

---

### Approach
- Applied **FinBERT** and **Aspect-Based Sentiment Analysis (ABSA)** to classify tone across executives and analysts.  
- Aligned sentiment trends with prudential metrics (CET1, NSFR, LCR, LDR) using pooled and per-bank time-series data.  
- Conducted rolling three-quarter correlation analysis to identify lead–lag sentiment patterns.  
- Developed **Power BI dashboards** visualising sentiment vs. prudential ratio dynamics.  
- Presented results to Bank of England representatives with interpretive insights on regulatory tone monitoring.

---

### Tools & Techniques
Python (Pandas, NumPy, FinBERT, Matplotlib, Seaborn)  
Power BI for interactive trend visualisation and presentation.

---

### Results
- Found measurable tone shifts between executive and analyst sentiment linked to liquidity and capital strength.  
- Observed **positive correlation (~+0.11)** between Lending/Deposit Ratios (LDR) and overall sentiment, suggesting optimistic tone during active lending phases.  
- Identified cautious language coinciding with CET1 capital build periods.  
- Delivered clear, explainable visualisations of tone–metric convergence.

---

### Key Learning
This project demonstrated the power of **financial NLP** in contextualising regulatory and prudential data.  
It reinforced my ability to integrate **language models with quantitative analysis**, communicate technical findings clearly, and collaborate within a multi-disciplinary data science team.
