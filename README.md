# Logistic Regression with Regularization – A Practical Guide

This repository contains a tutorial project on **Logistic Regression** with **Regularization** (L1 – Lasso and L2 – Ridge).  
The aim of this project is to demonstrate how logistic regression works, the challenges it faces (like overfitting), and how regularization techniques improve model performance and generalization.

---

## Project Overview
- Implemented **Logistic Regression** for binary classification using the **Breast Cancer dataset** from Scikit-learn.
- Compared:
  - Logistic Regression without Regularization
  - Logistic Regression with **L1 (Lasso)**
  - Logistic Regression with **L2 (Ridge)**
- Evaluated models using accuracy, precision, recall, F1-score, and ROC-AUC.
- Analyzed feature importance and the impact of regularization.

---

## Tech Stack
- **Programming Language**: Python  
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn  
- **Tools**: Jupyter Notebook  

---

## Repository Structure
- `Machine Learning Tutorial.ipynb` → Jupyter Notebook with full implementation  
- `Machine Learning Tutorial.pdf` → PDF version of the report/tutorial  
- `README.md` → Project documentation  
- `LICENSE` → MIT License  

---

## Key Results
- All models achieved **>90% accuracy** and **AUC-ROC > 0.97**.
- **L1 (Lasso)** helped in **feature selection**, reducing some coefficients to zero.  
- **L2 (Ridge)** improved model **stability** in the presence of multicollinearity.  
- Regularized models performed slightly better than the non-regularized baseline.

---

## Conclusion
Logistic Regression is a powerful baseline model for binary classification.  
- **L1 Regularization (Lasso)** → Useful for feature selection in high-dimensional datasets.  
- **L2 Regularization (Ridge)** → Helps in reducing coefficient magnitudes and improving generalization.  
- Regularization improved performance, preventing overfitting and enhancing interpretability.  

Future improvements may include:
- Exploring **ElasticNet** (a combination of L1 + L2).  
- Extending the model to **multi-class classification** problems.  

---

## License
This project is licensed under the [MIT License](./LICENSE).

