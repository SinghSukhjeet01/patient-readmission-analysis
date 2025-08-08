Patient Hospital Readmission Analysis

📋 Overview

This project investigates the key drivers behind patient hospital readmissions. By combining data preprocessing, exploratory data analysis (EDA), and machine learning models, we aim to uncover patterns that can help healthcare providers:

Improve patient care.

Reduce avoidable readmissions.

Optimize hospital resource allocation.


🎯 Background & Motivation

Hospital readmissions are a major concern in healthcare systems worldwide:

They increase healthcare costs significantly.

They are often preventable with timely interventions.

They can be indicators of inadequate care, poor discharge planning, or insufficient follow-up.


By analyzing hospital data, we aim to:

1. Identify which patients are most at risk of being readmitted.
2. Provide actionable insights for preventive care programs.
3. Support data-driven decision-making in hospital management.

📊 Dataset

Source: Includes patient medical history, treatments, and readmission status.

Example Attributes:

patient_id: Unique identifier.

age: Patient age group.

diagnosis: Primary diagnosis.

length_of_stay: Duration of hospital stay (days).

readmission_status: Binary indicator (Yes/No).

💻 Technical Stack

This project uses:

Languages: Python 3.x

Data Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn, Plotly

Machine Learning: Scikit-learn

Notebooks: JupyterLab


🔍 Methodology

The workflow is structured as follows:

1. Data Cleaning – Handle missing values, correct data types, and remove duplicates.


2. EDA – Visualize trends, correlations, and distributions.


3. Feature Engineering – Create meaningful variables to improve model performance.


4. Modeling – Train and evaluate machine learning models (Random Forest).


5. Evaluation – Assess models using Accuracy, Precision, Recall, F1-score
