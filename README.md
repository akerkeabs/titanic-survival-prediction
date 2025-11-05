# Titanic Survival Prediction

End-to-end machine learning project predicting passenger survival on the Titanic using **Logistic Regression**, **Decision Tree**, and **Random Forest** models.

---

## Goal
Predict whether a passenger survived based on features such as **Age**, **Sex**, **Fare**, and **Class**.

Dataset: [Kaggle Titanic Challenge](https://www.kaggle.com/competitions/titanic)

---

## Model Results

| Model | Accuracy | F1 | ROC-AUC |
|-------|-----------|----|---------|
| Logistic Regression | 0.80 | 0.73 | 0.84 |
| Decision Tree | 0.76 | 0.70 | 0.79 |
| Random Forest | **0.79** | **0.73** | **0.83** |

> The **Random Forest** achieved the best overall performance and generalization.

---

## Key Insights
- The most important predictors were **Sex**, **Fare**, and **Age**.  
- Tree-based models captured nonlinear relationships better than Logistic Regression.  
- Ensemble methods (Random Forest) reduced variance and improved stability.

---

## Tech Stack
Python · pandas · scikit-learn · seaborn · matplotlib · joblib

---

## Project Structure
Titanic_Survival_Prediction/
├── Titanic_Survival_Prediction.ipynb
├── models/
│ ├── titanic_logreg_scaled_pipeline.joblib
│ ├── titanic_decision_tree.joblib
│ └── titanic_random_forest.joblib
├── train.csv
├── test.csv
├── requirements.txt
└── README.md


---

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook Titanic_Survival_Prediction.ipynb


---

👤 **Author**

Akerke Absalykova
Data Science Portfolio 2025
🌐 GitHub Profile: https://github.com/akerkeabs

💼 LinkedIn: https://www.linkedin.com/in/akerke-absalykova/
