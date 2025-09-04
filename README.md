# Heart Disease Prediction using Logistic Regression

## Overview
This project uses **Logistic Regression** to predict whether a person has heart disease based on medical attributes.  
The dataset contains **303 patient records** with 13 health features such as age, cholesterol level, resting blood pressure, etc.  

## Dataset
- Source: UCI Heart Disease Dataset  
- Features: age, sex, chest pain type, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal  
- Target: `1 = Heart Disease`, `0 = Healthy Heart`

## Workflow
1. **Data Collection & Cleaning**  
   - Loaded the dataset into Pandas, checked for missing values, and performed statistical analysis.  

2. **Feature & Target Split**  
   - Independent variables (13 features)  
   - Dependent variable: `target`  

3. **Train-Test Split**  
   - Training set: 80%  
   - Test set: 20% (stratified sampling to maintain balance)  

4. **Model Training**  
   - Logistic Regression using **scikit-learn**  

5. **Evaluation**  
   - Training Accuracy: ~85%  
   - Test Accuracy: ~82%  

6. **Predictive System**  
   - Example input can classify whether a new patient is likely to have heart disease.  

## Technologies Used
- Python  
- Pandas, NumPy  
- scikit-learn  

## Results
- Accuracy on Training Data: **85%**  
- Accuracy on Test Data: **82%**

## How to Run
1. Clone this repository  
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
