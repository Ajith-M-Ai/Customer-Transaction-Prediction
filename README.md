# Customer Transaction Prediction

## Project Overview
Machine learning project to predict whether a customer will perform a future transaction using anonymized banking data. The project focuses on model comparison and evaluation to identify the best-performing classification algorithm.

---

## Problem Statement
The objective of this project is to build a machine learning model that predicts whether a customer will perform a transaction in the future, regardless of the transaction amount. The dataset is anonymized and structured to resemble real-world banking data, making it suitable for predictive modeling in financial applications.

---

## Dataset
- The dataset consists of anonymized banking data  
- Contains **200 numerical features** along with:
  - `ID_code` – Unique customer identifier
  - `target` – Binary variable  
    - `0` → Customer will not perform a transaction  
    - `1` → Customer will perform a transaction
- Feature names are anonymized, so domain-specific interpretation is not possible

---

## Approach
- Data loading and inspection  
- Handling missing values and data preprocessing  
- Feature scaling for high-dimensional data  
- Model training using multiple machine learning algorithms  
- Model evaluation and comparison  
- Selection of the best-performing model based on evaluation metrics  

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

## Machine Learning Models
- Logistic Regression  
- Random Forest  
- Gradient Boosting  

---

## Model Evaluation
The models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-score  

The best-performing model was selected based on overall performance and generalization ability.

---

## Results
The final model successfully identifies customers who are more likely to perform future transactions. This helps financial institutions proactively target high-potential customers and improve transaction forecasting.

---

## Challenges Faced
- High-dimensional anonymized feature space  
- Limited feature interpretability  
- Model selection and tuning  

These challenges were addressed using feature scaling, careful preprocessing, and model comparison techniques.

---

## Conclusion
This project demonstrates an end-to-end machine learning workflow for customer transaction prediction using anonymized banking data. The solution can be extended further with advanced feature selection and hyperparameter tuning.

---

## Author
**Ajith M**  
Aspiring AI/ML Engineer

