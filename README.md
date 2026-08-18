# 🦠 H1N1 Vaccine Prediction Dashboard (Python & Machine Learning)
## 📌 Project Overview
This project is a **H1N1 Vaccine Uptake Prediction Model** built using **Python, Pandas, and Scikit-learn**. It analyzes survey data on health behaviors, demographics, and personal opinions to predict whether an individual received the H1N1 vaccine. The project delivers business insights through EDA, data cleaning, feature engineering, and a fully tuned Logistic Regression model.
---
## 🎯 Project Objectives
- Analyze overall vaccination uptake patterns.
- Identify key demographic and behavioral drivers of vaccination.
- Handle missing values and outliers systematically.
- Address class imbalance in the target variable.
- Compare multiple feature engineering strategies.
- Build and evaluate a Logistic Regression classification model.
- Optimize the decision threshold for best F1-score.
---
## 🛠 Tools & Features Used
- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook
- StratifiedKFold Cross-Validation
- Feature Scaling (StandardScaler, MinMaxScaler)
- L1-Regularized Feature Selection
- Polynomial/Interaction Features
- Data Cleaning & Missing Value Imputation
- Outlier Detection (Z-score & IQR)
---
## 📈 Key Performance Indicators (KPIs)
- 🎯 Validation F1-Score
- ✅ Accuracy
- 🎯 Precision
- 🔁 Recall
- ⚖️ Train vs Validation Gap (Overfitting Check)
---
## 📊 Model Experiments
- Baseline Logistic Regression (raw features)
- Scaling Comparisons (None vs Standard vs MinMax)
- Class-Weight Balancing for Imbalanced Target
- Top-K Important Feature Selection (L1-based ranking)
- Polynomial & Interaction Feature Engineering
- Final Model Refit & Held-Out Test Evaluation
- F1-Optimal Threshold Tuning
---
## 📁 Dataset Information
The dataset includes:
- Unique ID
- H1N1 Worry & Awareness
- Antiviral Medication Use
- Preventive Behaviors (mask, hand-washing, avoidance)
- Doctor Recommendations (H1N1 & Seasonal)
- Health & Risk Perceptions
- Chronic Medical Condition
- Health Worker Status
- Health Insurance Status
- Demographics (Age, Sex, Race, Income, Marital Status, Employment)
- Household Composition (Adults, Children)
- Target: H1N1 Vaccine (0/1)
---
## 📌 Business Insights
- Identified the strongest predictors of vaccine uptake (e.g. doctor recommendation, risk perception).
- Compared scaling and class-balancing strategies for imbalanced classification.
- Selected the top contributing features using L1 regularization.
- Achieved improved F1-score through threshold tuning instead of the default 0.5 cutoff.
- Verified minimal overfitting by comparing train vs validation performance.
---
## 🚀 Skills Demonstrated
- Data Cleaning
- Missing Value & Outlier Treatment
- Feature Engineering
- Handling Imbalanced Data
- Model Building & Evaluation
- Cross-Validation
- Threshold Optimization
- Machine Learning Reporting
## Author
**Kanishka Agarwal**
👨‍💻 Data Analyst / Data Scientist
