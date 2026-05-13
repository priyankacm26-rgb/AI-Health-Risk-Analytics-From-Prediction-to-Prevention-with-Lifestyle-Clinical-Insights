# AI Health Risk Analytics: From Prediction to Prevention with Lifestyle & Clinical Insights

## Overview
AI Health Risk Analytics is a machine learning and data analytics project that predicts chronic disease risk using clinical and lifestyle-related data. The project focuses on identifying high-risk individuals early and providing actionable insights for preventive healthcare.

The solution combines machine learning models with interactive Power BI dashboards to transform healthcare data into meaningful predictions and visual analytics.

---

## Objectives
- Predict patient health risk levels using machine learning
- Analyze lifestyle and clinical factors affecting disease risk
- Provide interpretable insights for preventive healthcare
- Build interactive dashboards for healthcare analytics
- Support data-driven healthcare decision-making

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Power BI
- Joblib

---

## Project Workflow

### 1. Data Collection
Healthcare dataset containing:
- Demographic information
- Clinical measurements
- Lifestyle-related attributes
- Medical history indicators

### 2. Data Preprocessing
- Handling missing values
- Removing duplicates
- Feature encoding
- Data normalization
- Outlier handling

### 3. Exploratory Data Analysis (EDA)
Performed detailed analysis to identify:
- Health risk trends
- Correlation between features
- Distribution of patient attributes
- Disease risk patterns

### 4. Feature Engineering
Created meaningful features for improving model performance and prediction quality.

### 5. Machine Learning Models
Implemented and evaluated machine learning algorithms for risk prediction.

Example models:
- Logistic Regression
- Random Forest
- Decision Tree
- Support Vector Machine

### 6. Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 7. Risk Prediction System
The final system generates:
- Patient-level risk predictions
- Risk categories
- Explanation of contributing factors

### 8. Power BI Dashboard
Interactive dashboard includes:
- Patient risk distribution
- Lifestyle factor analysis
- Clinical insights
- Prediction summaries
- KPI visualizations

---

## Project Structure

```bash
AI-Health-Risk-Analytics/
│
├── data/
│   ├── healthcare_dataset.csv
│
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── eda_analysis.ipynb
│   ├── model_training.ipynb
│
├── models/
│   ├── final_model.pkl
│
├── dashboard/
│   ├── healthcare_dashboard.pbix
│
├── screenshots/
│   ├── dashboard.png
│
├── requirements.txt
├── README.md
└── app.py
