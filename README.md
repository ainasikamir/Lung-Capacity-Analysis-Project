# Lung-Capacity-Analysis-Project
### Overview
This project explores the relationship between lung capacity and various factors using Python and R. The dataset includes attributes such as height, age, gender, and smoking status. The project aims to identify significant predictors of lung capacity through data analysis and regression modeling.
### Dataset
The dataset LungCapData2.xlsx contains the following features:
Lung Capacity (LungCap): Continuous variable indicating lung volume.
Height: Height of the individual (predictor variable).
Age: Age of the individual.
Gender: Male or Female.
Smoking Status: Yes or No.
### Project Structure
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Developed and compared three regression models:
Model 1: Linear Regression (Lung Capacity vs. Height)
Model 2: Quadratic Regression (Lung Capacity vs. Height + Height²)
Model 3: Cubic Regression (Lung Capacity vs. Height + Height² + Height³)
- Model Comparison: Used ANOVA tests to assess model fit and statistical significance, selecting the most interpretable model with the best fit.
### Model Interpretation
Selected the quadratic model as the best fit, demonstrating the non-linear relationship between height and lung capacity without overfitting.
### Tools and Technologies
Languages: Python, R
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels (Python) 
Statistical Analysis: ANOVA testing, regression analysis
### Missing Dataset
The original dataset (`LungCapData2.xlsx`) is not included.
