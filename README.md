# Identifying TB Patients at Risk of Early Treatment Departure Using a Bayesian-Optimized XGBoost Model

This project implements a machine learning pipeline to predict the risk of early treatment departure (HAMA) among clinically diagnosed tuberculosis (TB) patients in the Philippines. Using XGBoost with Bayesian hyperparameter optimization (via Hyperopt), the model aims to assist healthcare practitioners in proactively identifying patients who may default on treatment, enabling timely intervention to improve outcomes.

---

## Background

Tuberculosis remains a significant public health challenge, particularly in resource-deficient areas. Early treatment departure (HAMA) undermines treatment efficacy and contributes to drug resistance. Predicting which patients are at risk provides an opportunity to implement targeted interventions to improve adherence.

---

## Features

- Utilizes clinical and treatment timeline data for prediction  
- Implements XGBoost classifier with Bayesian optimization using Hyperopt for hyperparameter tuning  
- Achieves 77% accuracy and 0.64 ROC AUC on test data  
- Modular and extensible pipeline for easy updates and feature additions

---

## Data

The dataset includes clinical, demographic, and treatment timeline data of TB patients diagnosed in the Philippines. 

*Note: Due to confidentiality, the raw data is not included in this repository, but I provided a link that points to the data source.*

---

## Modeling

- **Algorithm:** XGBoost Classifier  
- **Hyperparameter Optimization:** Bayesian optimization via `hyperopt`  
- **Evaluation Metrics:** Accuracy, ROC AUC

---

## Results

| Metric    | Score   |  
|-----------|---------|  
| Accuracy  | 0.77    |  
| ROC AUC   | 0.64    |

The model demonstrates moderate predictive ability and serves as a foundation for further improvements.

---

## Future Work

- Incorporate additional demographic features such as age, occupation, and education  
- Add comorbidity variables (e.g., HIV status, diabetes)  
- Explore other machine learning algorithms and ensemble methods  


---

*If you have any questions or feedback, feel free to contact me at jprmaulion[at]gmail[dot]com.*
