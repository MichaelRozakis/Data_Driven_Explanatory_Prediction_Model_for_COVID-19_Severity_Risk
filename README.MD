# Data-Driven Explanatory Prediction Model for COVID-19 Severity Risk

## Overview
The global spread of COVID-19 has placed unprecedented pressure on healthcare systems worldwide. This project presents an **integrated machine learning (ML) and deep learning (DL) framework** designed to predict the severity of COVID-19 cases among hospitalized patients. By leveraging advanced analytics, this model assists healthcare providers in identifying high-risk individuals and prioritizing interventions effectively.

## Datasets
- **Source**: General University Hospital of Patras
- **Time Period**: March 2020 - February 2022
- **Sample Size**: Two datasets, comprising 470 and 194 SARS-CoV-2 positive patients, respectively
- **Content**: Unprocessed clinical data collected at the initial stage of hospitalization

## Objectives
- **Unsupervised Patient Classification**: Automatically grouping patients into "Non-Severe," "Severe," and "Deceased" categories using **clustering techniques**.
- **Predictive Modeling**: Implementing **five ML** and **four DL models** to enhance the accuracy of severity risk prediction.
- **Explainable AI (XAI)**: Utilizing **SHapley Additive exPlanations (SHAP)** to improve model transparency and interpretability.

##  Methodology
### **1️⃣ Data Preprocessing**
- Data cleaning and feature engineering
- Handling missing values
- Feature selection

### **2️⃣ Machine Learning Models**
- **Logistic Regression**
- **Support Vector Machines (SVMs)**
- **Random Forest**
- **XGBoost**
- **Gradient Boosting**

### **3️⃣ Deep Learning Models**
- **Multilayer Perceptrons (MLPs)**
- **Autoencoders**
- **TabNets**
- **Convolutional Neural Networks (CNNs)**
- **Kolmogorov-Arnold Networks (KANs)** (*Best Performing Model*)

### **4️⃣ Class Imbalance Handling**
- **Synthetic Minority Over-Sampling Technique (SMOTE)** applied to address class imbalance

### **5️⃣ Explainability & Feature Importance Analysis**
- **SHAP (SHapley Additive exPlanations)** used to identify key clinical features contributing to predictions

## Key Findings
- **Kolmogorov-Arnold Networks (KANs) outperformed all models**, achieving:
  - **92% & 96% accuracy** in predicting severe COVID-19 outcomes
  - **83% & 87% accuracy** in forecasting mortality risk
- **Top Identified Clinical Features** impacting COVID-19 severity:
  - Lymphocytes, Neutrophils, Troponin levels, Age, Urea levels, INR, CRP, PO2, APTT, TNF, D-dimer, Hemoglobin, Dyspnea, Diabetes, Hypertension, Potassium (K), and LDH.
- **Robustness Across Variants & Vaccination Status**: The model demonstrated consistent performance across different COVID-19 strains and patient conditions, including vaccination status.

## Future Work
- Further refinement and optimization of **Kolmogorov-Arnold Networks (KANs)**
- Additional validation using diverse datasets and COVID-19 variants
- Investigating the impact of specific patient conditions on severity prediction


## Acknowledgments
Special thanks to the **General University Hospital of Patras** for providing the datasets and to my Supervisors: Dr. Seferina Mavroudi and Dr. Konstantinos Theofilatos for their contributions to **Explainable AI in Healthcare**.

