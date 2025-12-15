# Heart Disease Risk Prediction using Machine Learning

This project focuses on predicting the risk of heart disease using machine learning classification techniques.  
The analysis follows the **CRISP-DM methodology**, covering all stages from business understanding and data preparation to modelling, evaluation, and deployment.

The objective is to build reliable predictive models that can help identify patients at risk of heart disease, prioritising **recall and sensitivity** to minimise false negatives, which is critical in healthcare-related applications.

## Dataset
The project uses a public healthcare dataset containing demographic, clinical, and test-related variables such as age, cholesterol levels, blood pressure, ECG results, and exercise-induced indicators.

## Methodology
The project was structured according to the CRISP-DM framework:
- Business Understanding
- Data Understanding
- Data Preparation
- Modelling
- Evaluation
- Deployment

Data exploration and initial model screening were carried out using **RapidMiner**, followed by further modelling and optimisation in **Python**.

## Models Implemented
The following classification models were developed and evaluated:
- Logistic Regression
- Naive Bayes
- Gradient Boosted Trees

Model optimisation was performed using **Grid Search**, and performance was assessed using metrics such as accuracy, precision, recall, F1-score, and AUC.

## Key Results
All models achieved strong predictive performance.  
Based on the healthcare context and the need to minimise false negatives, the **Optimized Logistic Regression** model was selected as the most suitable for deployment.

## Tools and Technologies
- Python (pandas, scikit-learn, matplotlib)
- RapidMiner
- Jupyter Notebook

## Project Structure
- `.ipynb` file: Data analysis, modelling, and evaluation in Python  
- `.pdf` file: Full project report  
- RapidMiner files: Data preparation and AutoModel processes  
- Dataset file: Original data used for the analysis

## Disclaimer
This project is for educational and analytical purposes only and should not be used for real medical diagnosis or decision-making.
