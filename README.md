# life-expectancy-prediction
Life Expectancy Prediction using WHO dataset. Includes data preprocessing, multiple ML models (Linear Regression, Decision Tree, Random Forest, KNN, SVM), model evaluation, and visualization in Python &amp; Power BI. Random Forest achieved ~95% accuracy.

# Column Explanations of Life Expectancy Data,WHO data(csv)
1.	Country → Name of the country. (Categorical)
2.	Year → Year of observation. (Integer)
3.	Status → Whether the country is Developed or Developing. (Categorical)
4.	Life expectancy → Average number of years a newborn is expected to live. (Target column, float)
5.	Adult Mortality → Probability of dying between ages 15–60 per 1000 population. (Float)
6.	Infant deaths → Number of infant deaths per 1000 population. (Integer)
7.	Alcohol → Alcohol consumption (liters per capita per year). (Float)
8.	Percentage expenditure → Health expenditure as % of GDP per capita. (Float, usually very skewed)
9.	Hepatitis B → % of 1-year-old children with Hepatitis B immunization. (Float)
10.	Measles → Number of reported measles cases per 1000 population. (Integer)
11.	BMI → Average Body Mass Index of population. (Float)
12.	Under-five deaths → Number of deaths under age 5 per 1000 population. (Integer)
13.	Polio → % of 1-year-old children immunized against Polio. (Float)
14.	Total expenditure → Government expenditure on health as % of total government expenditure. (Float)
15.	Diphtheria → % of 1-year-old children immunized against Diphtheria. (Float)
16.	HIV/AIDS → Deaths per 1000 live births due to HIV/AIDS (0–4 years). (Float)
17.	GDP → GDP per capita (USD). (Float, has missing values)
18.	Population → Country population. (Float, missing values)
19.	Thinness 1-19 years → % of thinness (underweight) among 10–19 years. (Float)
20.	Thinness 5-9 years → % of thinness (underweight) among 5–9 years. (Float)
21.	Income composition of resources → Index (0–1) representing human development based on income, education, and life expectancy. (Float)
22.	Schooling → Average number of years of schooling. (Float)
________________________________________


# Life Expectancy Prediction Project

This repository contains a complete **Life Expectancy Prediction** project using WHO health dataset.  
The project applies **Machine Learning models in Python** and also includes a **Power BI dashboard** for visualization.  

## 📂 Project Components
- **Dataset**: WHO Life Expectancy Data (CSV format)  
- **Python Code**: Data preprocessing, model training, evaluation, and predictions  
- **Prediction Results**: CSV file with actual vs predicted life expectancy  
- **Power BI Visualization**: Dashboard analyzing life expectancy, health expenditure, and prediction results  

## ⚙️ Machine Learning Workflow
1. Import required libraries  
2. Load and explore dataset  
3. Data preprocessing (handling nulls, encoding categorical features)  
4. Feature selection and target variable definition  
5. Train-Test split  
6. Model training:
   - Linear Regression  
   - Decision Tree  
   - Random Forest  
   - KNN  
   - SVM  
7. Model evaluation (accuracy, error metrics)  
8. Best model selection (**Random Forest ~95% accuracy**)  
9. Prediction and visualization (scatter plot, actual vs predicted)  

## 📊 Visualization
- Python: Scatter plot of Actual vs Predicted  
- Power BI: Interactive dashboard showing Life Expectancy vs Expenditure, Immunization, and prediction errors  

## 🛠️ Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- Power BI  
- Jupyter Notebook  

## 🚀 Results
- Best Model: **Random Forest**  
- Accuracy: ~95%  
- Dashboard shows strong correlation between **health expenditure** and **life expectancy**  

---
