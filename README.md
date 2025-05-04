# NeuroNexus
# 🔍 ML Projects: Titanic Survival & Credit Card Fraud Detection

This repository contains two supervised machine learning projects submitted as part of the **Neuronexus ML Bootcamp**.

- 🚢 **Titanic Survival Prediction** – Predict whether a passenger would survive based on features like age, class, and gender.
- 💳 **Credit Card Fraud Detection** – Identify fraudulent transactions using a dataset of anonymized credit card data.



## 🚢 Titanic Survival Prediction

- **Objective:** Predict the survival of passengers aboard the Titanic.
- **Dataset Used:** `tested.csv` (Kaggle Titanic dataset)
- **Features:** Passenger class, sex, age, siblings/spouses, parents/children, fare, and embarkation point.
- **Model Used:** Random Forest with GridSearchCV for hyperparameter tuning.
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score.


## 💳 Credit Card Fraud Detection

- **Objective:** Detect fraudulent credit card transactions from anonymized data.
- **Dataset Used:** `creditcard.csv` (contains highly imbalanced real-world transaction data)
- **Techniques Used:**
  - Data preprocessing and scaling
  - Class imbalance handling using undersampling
  - Model training using Random Forest and Logistic Regression
- **Evaluation Metrics:** ROC-AUC, Precision, Recall, F1-Score


## 🧠 Tools & Technologies

- Python 3.x
- Jupyter Notebook
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn (for visualization)

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/neuronexus-ml-projects.git
   cd neuronexus-ml-projects
