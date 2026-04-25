# Bank Marketing
**Course:** BCIS 466 
**Instructor:** Dr. Don Fuqua  
**Student:** Manuel Corona  

## Project Overview
This semester project applies machine learning workflows to a real-world dataset from a Portuguese banking institution. The goal is to predict whether a client will subscribe to a term deposit (variable 'y') based on 16 features including demographics, financial status, and previous marketing interactions.

## Key Requirements Met
* **Observations:** 45,211 (Requirement: >1,000)
* **Features:** 16 (Requirement: 5-10)
* **Algorithm:** Random Forest Classifier (Comparison with Logistic Regression)
* **Tools:** Python, Pandas, Scikit-Learn, Seaborn

## Model Performance
The Random Forest model was selected as the final model due to its robustness with imbalanced data:
* **Accuracy:** 90.5%
* **F1-Score:** 0.51
* **Key Feature:** 'Duration' was identified as the most significant predictor for customer conversion.

## How to Run
1. Open the `.ipynb` file in Google Colab.
2. Ensure `ucimlrepo` is installed (`!pip install ucimlrepo`).
3. Run all cells to reproduce the EDA, preprocessing, and model training.
