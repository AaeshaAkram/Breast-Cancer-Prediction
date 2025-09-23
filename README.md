# Breast Cancer Prediction

## Overview
This project applies **machine learning classification** to predict breast cancer diagnoses (benign vs. malignant) using patient medical data.  
The workflow was designed in **KNIME** and also implemented in **Python** (Jupyter Notebook), achieving high accuracy in distinguishing between benign and malignant tumors.  

## Key Contributions
- Designed a complete ML pipeline for breast cancer diagnosis  
- Preprocessed and cleaned medical dataset (handled missing values, normalized features)  
- Trained models in both **KNIME** and **Python**  
- Evaluated models using Accuracy, Confusion Matrix, and ROC-AUC   

## Tech Stack
- KNIME Analytics Platform  
- Python (Scikit-Learn, Pandas, NumPy, Matplotlib, Jupyter Notebook)  
- Models: Logistic Regression

## Repository Contents
- `breast_cancer_prediction.ipynb` – Python notebook implementation  
- `knime_breast_cancer_prediction.pmml` – KNIME workflow model  
- `BreastCancer_prediction.joblib` – Serialized trained model  
- `data.csv` – Input dataset  

## Results
- Achieved **>90% accuracy** in classifying tumors as benign or malignant  
- ROC-AUC scores consistently above 0.97  
- Confusion Matrix analysis shows very low false negatives (critical in medical use)  

