# Covid Outcome Prediction 🦠

Predicting whether a patient tests **COVID-19 positive or negative** using supervised machine learning — comparing 7+ classification algorithms to identify the best-performing model.

---

## Problem Statement
Early and accurate prediction of COVID-19 outcomes can support healthcare resource planning and patient triage. This project builds and evaluates multiple ML classifiers to predict patient outcome (positive/negative) based on clinical and demographic features.

---

## Results

| Metric | Score |
|--------|-------|
| Best Model | Extra Trees Classifier |
| Accuracy | 78.04% |
| Precision | 0.78 |
| Recall | 0.78 |
| F1-Score | 0.78 |

> Extra Trees Classifier selected for its superior recall on the positive class — minimising false negatives is critical in a medical diagnosis context.

---

## Models Compared
- Decision Tree & Tuned Decision Tree
- Support Vector Classifier (SVC)
- K-Nearest Neighbours
- Logistic Regression
- Random Forest
- Extra Trees Classifier ✅ *(best performer)*
- Grid Search CV (hyperparameter tuning)

---

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## Dataset
- **Source:** Covid-19 clinical dataset
- **Task:** Binary classification (positive / negative)

---

## Project Structure

Covid-Outcome-Prediction/
│
├── Covid Predictions.ipynb   # Full notebook with EDA, modelling, evaluation
└── README.md

---

## Key Learning
Explored the trade-off between accuracy and recall in medical ML — a model optimised purely for accuracy can miss positive cases. Extra Trees' ability to maintain recall while achieving strong accuracy made it the preferred model for this use case.

