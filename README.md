> ⚠️ **Note:** This repository contains the original Forage job simulation 
> (Tasks 1–4). It served as the foundation for a much more advanced system. 
> For the full Agentic AI build — with reasoning, memory, ethical guardrails, 
> and Streamlit deployment — see 👉 [CreditRiskAI-Agentic-Collections](https://github.com/fisayojiboye/CreditRiskAI-Agentic-Collections)

> # Tata iQ - GenAI Powered Data Analytics | Forage Virtual Experience

**Role**: AI Transformation Consultant  
**Client**: Geldium Finance  
**Program**: GenAI Powered Data Analytics Job Simulation by Tata iQ

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-FF9F00?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 📋 Project Overview

This project simulates my work as an **AI Transformation Consultant at Tata iQ**, helping **Geldium Finance** — a digital lending company — reduce its high credit card delinquency rate using GenAI and advanced analytics.

The goal was to move beyond traditional manual collections by building an intelligent, ethical, and explainable AI solution that identifies at-risk customers early and recommends the most effective intervention strategies.

---

## 🎯 Project Objectives

- Perform Exploratory Data Analysis (EDA) and improve data quality
- Build a predictive model to forecast customer delinquency
- Translate model insights into actionable business recommendations
- Design a high-level **AI-powered autonomous collections system** with strong ethical guardrails

---

## Project Structure

Tata-iQ-GenAI-Data-Analytics-Forage/
├── README.md                          ← Main project documentation
├── LICENSE                            ← Optional (MIT or Apache)
├── requirements.txt                   ← List of Python packages
├── .gitignore                         ← Ignore unnecessary files
│
├── data/
│   ├── raw/
│   │   └── Delinquency_prediction_dataset.xlsx     ← Original file
│   └── processed/
│       ├── Cleaned_Delinquency_Dataset.xlsx
│       └── Final_Dataset_with_New_Target.xlsx
│
├── notebooks/
│   ├── 01_EDA_Task1.ipynb
│   ├── 02_Predictive_Modeling_Task2.ipynb
│   ├── 03_Business_Recommendations_Task3.ipynb
│   └── 04_Agent_Prototype.ipynb               ← (I will add this later)
│
├── reports/
│   ├── Task1_EDA_Report.pdf
│   ├── Task2_Model_Report.pdf
│   └── Task3_Business_Recommendations.pdf
│
├── visuals/
│   ├── delinquency_boxplots_improved.png
│   ├── feature_importance.png
│   └── confusion_matrix.png
│
└── presentation/
    └── Task4_Final_Presentation.pptx                                  

---
  
## 🛠️ Tech Stack

- **Programming Language**: Python 3
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn (Decision Tree Classifier)
- **Environment**: Jupyter Notebook
- **Other Tools**: GenAI (Grok, ChatGBT) for code generation, insights, and report structuring

---

## 📊 Key Results & Achievements

### Task 1: Exploratory Data Analysis
- Cleaned inconsistent data and handled missing values using group median imputation
- Identified `Missed_Payments` and `Credit_Utilization` as the strongest risk indicators
- Created an improved target variable (`Delinquent_Account_New`) for better model learning

### Task 2: Predictive Modeling
- Built a **Decision Tree model** achieving:
  - **Accuracy**: 83%
  - **AUC-ROC**: 0.868
  - **F1-Score**: ~0.83 (balanced)
- `Missed_Payments` contributed **62.17%** to model decisions

### Task 3: Business Recommendations
- Developed a **SMART intervention strategy**: Targeted SMS + flexible payment plan pilot for high-risk customers
- Goal: Reduce 30+ day delinquency by **15%** in the pilot group

### Task 4: AI-Powered Collections System
- Designed a conceptual **Agentic AI Collections System** with:
  - Real-time risk scoring
  - Autonomous decision-making with human oversight
  - Strong ethical guardrails (fairness, explainability, compliance)

---

## 🚀 What I Learned

- The importance of **data quality** and thoughtful feature engineering in financial modeling
- How to improve weak target variables using domain logic
- The critical balance between model performance and **explainability** in regulated industries
- How to translate technical insights into clear business recommendations
- The value of **Agentic AI** and responsible AI design (guardrails, bias detection, human-in-the-loop)

This simulation gave me hands-on experience in the full lifecycle of an AI project in financial services — from raw data to strategic automation.

---

## 🙋‍♂️ Connect With Me

I'm actively seeking opportunities in **Dtata Science, Data Analytics, AI/ML, and Financial Services**.  

Feel free to connect if you're working on similar projects or have any feedback!

---
