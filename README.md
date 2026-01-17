# Data Science Projects

A curated collection of applied data science and machine learning projects, focusing on real-world problem solving, model evaluation, and business interpretation.

---

## Tools & Skills

**Languages:** Python, SQL, R  
**Libraries:** pandas, numpy, matplotlib, scikit-learn, XGBoost, LightGBM  
**Tools:** Google Colab, GitHub, Tableau, Excel  
**Concepts:** Credit Risk Modeling, A/B Testing, Classification, Regression, Clustering, Time Series, Feature Engineering, Model Evaluation

---

## Projects Overview

### 1. Credit Risk Modeling with Application & Behavioral Credit Records  
📓 *Notebook:* [Predicting Credit Default Risk](Predicting_Credit_Default_Risk.ipynb)
📄 *PDF:* [Credit Risk Modeling – Project Report](Predicting_Credit_Default_Risk.pdf)

Built an **end-to-end credit risk modeling pipeline** using applicant profiles and historical credit behavior data.  
Constructed default labels from credit records, engineered behavior-based features, and compared multiple tree-based ensemble models.

**Highlights:**
- Custom target definition derived from repayment history  
- Handled class imbalance and evaluated models using ROC-AUC  
- Compared Random Forest, XGBoost, and LightGBM  
- Translated predicted probabilities into risk bands for business interpretation

---
### 2. Ads CTR Prediction with Large-Scale Online Advertising Data

📓 *Notebook:* [CTR Data Processing & Baseline Models](CTR_Data_Processing_and_Baseline_Models_High_Cardinality.ipynb)  
📓 *Notebook:* [CatBoost – Final Model (Class Weights & Tuning)](CTR_CatBoost_Final_Model_Class_Weights_and_Tuning.ipynb)  
📄 *PDF:* [Ads CTR Prediction – Project Overview](Ads_CTR_Prediction_Project_Overview.pdf)  
📄 *PDF:* [Ads CTR Prediction – Final Report](Ads_CTR_Prediction_Project_Final_Report.pdf)

Built a **scalable click-through rate (CTR) prediction pipeline** on large-scale online advertising impression data (30M+ rows).  
Designed a leakage-aware modeling workflow for **high-cardinality, sparse categorical features**, with an emphasis on probabilistic prediction quality and **log-loss optimization** for real-world ad ranking systems.

**Highlights:**
- Processed large-scale CTR data with severe class imbalance using stratified sampling (30M → 1M)  
- Engineered leakage-safe feature pipelines for high-cardinality categorical variables  
- Established strong baselines with Logistic Regression and Random Forest  
- Trained and tuned a CatBoost model with class weights and early stopping  
- Achieved significant log-loss improvement over baseline models with well-calibrated click probability estimates

---

### 3. Clustering Algorithms with Scikit-learn  
📄 *PDF:* [Clustering Algorithms with Scikit-learn](Clustering_Algorithms_SciKit_Learn.pdf)

Explored **KMeans**, **DBSCAN**, and **Agglomerative Clustering** on real-world customer datasets.  
Used Elbow and Silhouette methods to determine optimal clusters and visualized results in 2D and 3D.

---

### 4. Time Series Forecasting with LSTM  
📄 *PDF:* [Time Series Forecasting with LSTM](Time_Series_Forecasting_with_LSTM.pdf)

Applied **LSTM neural networks** to forecast energy consumption time series, focusing on sequence preparation, scaling, and model evaluation.

---

### 5. Detecting AI-Generated Text using LLMs  
📄 *PDF:* [Detecting AI-Generated Text using LLMs](LLM_detect_ai_generated_text.pdf)

Investigated how **Large Language Models** can distinguish between human-written and AI-generated text.

---

### 6. Re-ranking QA Answers with LLMs  
📄 *PDF:* [Re-ranking QA Answers with LLMs](LLMs_Hypothetical_Answers_ReRank_QA_T...)

Explored methods to improve question-answering systems by generating and reranking candidate answers using LLMs.

---

### 7. XGBoost from Scratch  
📄 *PDF:* [XGBoost from Scratch](XGBoost_from_Scratch_in_Python.pdf)

Implemented **XGBoost from scratch** to deeply understand boosting mechanics, tree construction, and regularization.

---

### 8. Recommendation System – Collaborative Filtering  
📓 *Notebook:* [Recommendation System – Collaborative Filtering](Recommendation_system_collaborative_filltering.ipynb)

Developed **user-based** and **item-based** collaborative filtering models using the Amazon 2023 All Beauty reviews dataset.  
Built a user–item rating matrix, computed cosine similarity, and evaluated performance using RMSE and precision@k.

---

## Author

**Lin (Jocelyne) Zhu**  
