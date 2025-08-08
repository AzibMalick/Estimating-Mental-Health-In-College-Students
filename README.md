**Depression Risk Prediction in Students using Machine Learning:**

This project uses the Student Lifestyle and Behavioral Dataset to predict whether a student is likely to experience depression based on factors such as sleep duration, academic pressure, anxiety levels, and relationship quality.

Two models were developed and compared:

XGBoost
Gradient Boosting

---

**Features of the Project:**

Cleaned and preprocessed dataset with categorical encoding
Data standardization for numerical features
Machine Learning model training and hyperparameter tuning
Confusion matrices, classification reports, and accuracy comparison
Feature importance analysis for biomedical interpretation
Export-ready report (PDF)

---

**Dataset Overview:**

**Source:** Depression in Students Dataset (Kaggle / academic source)
**Target column:** Depression (1 = depression present, 0 = not present)
**Observations:** 1000+
**Features include:** Sleep Duration, Academic Pressure, Anxiety Levels, Relationship Quality, Self-reported Depression Status

---

**Model Performance:**

**XGBoost (Baseline):**	67.00%

**Gradient Boosting (Baseline):**	61.00%

**XGBoost (Tuned):**	84.90%

**Gradient Boosting (Tuned):**	85.90% ✅

Tuned Gradient Boosting slightly outperformed XGBoost, with both models showing significant improvements over baseline results.


---

**What We Learned:**

From both model training and feature analysis, we found that:

**1.** Sleep duration, academic pressure, and anxiety levels were the strongest predictors of depression risk.

**2.** Hyperparameter tuning provided substantial performance gains, making the models suitable for practical mental health screening tools.

**3.** These predictive models could be integrated into digital mental health triage systems for early detection and targeted intervention.

---

**Files in the Repo:**

**depression-risk-prediction.ipynb** – Jupyter Notebook source code

**student_depression_dataset.csv** – Dataset used for training and testing

**requirements.txt** – Required Python libraries

**depression-prediction-report.pdf** – Final formatted report (optional)

**README.md** – Project overview (this file)

---

**Future Work:**

Apply SMOTE for handling class imbalance

Add additional features such as wearable device metrics

Deploy as a Streamlit or Flask application for real-time prediction

Explore multi-modal models combining survey and physiological data

---

**Conclusion:**

This project demonstrates how machine learning can be effectively applied in the biomedical and educational domains to detect early signs of mental health issues among students.
From a biomedical engineering perspective:

The methodology aligns with evidence-based risk assessment by combining psychological, lifestyle, and academic stress indicators.

The pipeline can be integrated into digital health monitoring platforms for proactive mental health management.

The feature importance analysis helps clinicians and counselors prioritize intervention strategies for high-risk individuals.

By combining data science with domain knowledge in healthcare, such models move one step closer to preventive mental health care, reducing long-term social and medical costs.

---

**Author:**

Developed by Azib Malick

Email: azibmalick25@gmail.com

© 2025 Azib Malick. All rights reserved.
