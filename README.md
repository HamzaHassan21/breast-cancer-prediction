# Breast Cancer Outcome Prediction Using Machine Learning

This project applies machine learning to predict two key outcomes for breast cancer patients:

- **Survival Status** — Will the patient survive? (Classification)
- **Progression-Free Months** — How long until the disease progresses? (Regression)

By combining medical data with predictive models, this project aims to assist in more accurate, data-driven clinical decisions that could improve patient care and outcomes.

---

## Project Highlights

 **Goal**: Predict patient outcomes using clinical features such as stage, treatment history, and lymph node involvement.

🛠 **Tech Stack**:  
Python · Pandas · Scikit-learn · Matplotlib · Seaborn · SMOTE · Random Forest · Logistic Regression

 **Key Results**:
- Achieved strong classification accuracy and recall for mortality prediction
- Identified top clinical features driving outcomes (e.g., cancer stage, lymph nodes, treatment type)
- Demonstrated model interpretability and practical healthcare relevance

---

## Notebooks Overview

 **Notebook 1: Data Cleaning & EDA**  
- Removed irrelevant columns (e.g., Patient ID, Profession)  
- Handled missing data and encoded categorical variables  
- Explored survival patterns through visualizations and correlations

 **Notebook 2: Model Training & Evaluation**  
- Balanced imbalanced data using oversampling (SMOTE)  
- Trained classification and regression models  
- Evaluated performance using metrics like F1-score and RMSE

 **Notebook 3: Model Optimization & Final Insights**  
- Applied hyperparameter tuning (GridSearch, RandomizedSearch)  
- Interpreted feature importance using Random Forest  
- Summarized clinical insights and model impact

---

##  Real-World Impact

This project highlights how machine learning can:
- Enhance early detection of high-risk patients
- Personalize treatment strategies
- Support oncologists with objective, data-driven tools

It’s a small but meaningful step toward precision medicine.

---

## How to Use

1. Clone the repository:
```bash
git clone https://github.com/yourusername/breast-cancer-prediction.git
