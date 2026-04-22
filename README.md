# Employee-Retention-analysis
Built ML model to predict job-switch likelihood. 

This is a professional and visually impactful documentation layout for your **Employee Retention Prediction** Capstone project. This structure is designed to highlight your high-level data science skills, from advanced preprocessing to executive-level model selection.

---

# 📊 Predictive Analytics for Employee Retention
> **Leveraging Machine Learning to Mitigate Attrition Risks**
> This Capstone project focuses on developing a high-precision classification system to predict the probability of Data Scientists seeking a job change, enabling HR departments to implement proactive retention strategies.

---

## 🏗️ Technical Pipeline Overview

### 1. Data Intelligence & Preprocessing
The foundation of the project involves transforming raw behavioral and demographic data into a machine-learnable format.
* **Feature Engineering:** Refined variables such as `city_development_index`, `relevant_experience`, and `training_hours` to capture deep correlations.
* **Handling Class Imbalance:** Applied **SMOTE (Synthetic Minority Over-sampling Technique)** to address the skewed nature of attrition data, ensuring the model doesn't overlook employees likely to leave.
* **Missing Value Strategy:** Implemented sophisticated imputation to maintain dataset integrity across categorical and numerical features.

### 2. Model Architecture & Comparison
We evaluated multiple industry-standard algorithms to find the optimal balance between precision and recall.

| Model | Strategic Role | Performance Insight |
| :--- | :--- | :--- |
| **XGBoost** | **Primary Predictor** | **Top Performer.** Achieved the highest ROC-AUC (0.8167), offering the best balance for risk ranking. |
| **LightGBM** | **Efficiency Leader** | Optimized for high-speed processing with a strong focus on high-recall detection. |
| **Random Forest** | **Robust Ensemble** | Delivered exceptional recall (~0.80), identifying the majority of at-risk employees. |
| **Logistic Regression** | **Baseline Metric** | Provided a stable, interpretable benchmark for business stakeholders. |

### 3. Key Findings & Executive Insights
* **Primary Drivers:** Analysis identified that experience levels and city development indices are the strongest indicators of job-change behavior.
* **Risk Segmentation:** The model successfully segments employees into "Probability Buckets," allowing HR to prioritize intervention resources for high-risk talent.

---

## 🛠️ Tech Stack & Methodology
* **Programming:** Python (Pandas, NumPy)
* **Machine Learning:** Scikit-Learn, XGBoost, LightGBM
* **Data Visualization:** Matplotlib, Seaborn
* **Advanced Techniques:** SMOTE for imbalance handling, Hyperparameter Tuning, ROC-AUC Optimization

---

## 📈 Executive Summary: The "XGBoost" Advantage
Following a rigorous evaluation, **XGBoost** was selected as the production model. It provides the most reliable "Risk Ranking" system, which is critical for:
1.  **Talent Retention:** Targeting the right people before they initiate a transition.
2.  **Recruitment Planning:** Forecasting future vacancies with higher accuracy.
3.  **Resource Allocation:** Optimizing the HR budget by focusing on high-value, high-risk segments.

---

### 💡 Project Deliverables
* **`Employee_Retention.ipynb`**: Full end-to-end data science pipeline (cleaning to evaluation).
* **`Retention_Analysis.pptx`**: Strategic business presentation for executive stakeholders.
* **`aug_train.csv`**: Comprehensive training dataset featuring real-world data scientist demographics.

---
*Transforming workforce data into actionable organizational stability.*
