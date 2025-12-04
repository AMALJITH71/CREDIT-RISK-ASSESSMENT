# Credit Risk Assessment — Loan Default Prediction with Stats & Machine Learning
Welcome to my deep dive into Credit Risk Assessment using real-world loan data!
This project blends Probability, Statistical Analysis, and Machine Learning to predict the likelihood of loan default — enabling smarter financial decisions and more reliable risk management in lending systems

## 🎯 Project Idea & Motivation

With the rapid digital transformation of the financial sector, lending institutions now depend heavily on data-driven techniques to evaluate borrower creditworthiness. Traditional scoring systems work, but they often fail to capture deeper patterns present in large-scale financial datasets.

I built this project with the goal of applying statistics + machine learning to develop a more interpretable and reliable credit risk prediction system, rather than a black-box scoring approach.

## 💡 Why This Project?

🔹 Real-World Financial Value
Credit risk modelling is a core component of banking and loan operations. With platforms like LendingClub providing public historical datasets, this domain offers an excellent opportunity to develop practical, impactful models.

🔹 Where Finance Meets Data Science
This project allowed me to apply feature engineering, probability, EDA and ML modelling to solve a problem that affects millions of borrowers and lenders globally.

🔹 Focus on Explainability
Instead of depending only on accuracy, I emphasize interpretable insights — using distributions, correlation analysis, and importance metrics to understand why defaults occur, not just whether they will.

## 🎓 What I Wanted to Learn

✔ Apply statistical thinking to real business datasets
✔ Visualize how financial factors influence loan outcomes
✔ Identify features that truly matter in default prediction
✔ Build an end-to-end ML pipeline in a finance-critical setting

##  📁 Project Overview

Objective: Predict whether a loan will default using historical borrower and loan data, enriched with statistical insights and ML models.

##  📊 Exploratory Data Analysis (EDA)

📌 Histograms & Box-plots — detect distributions, skewness, and outliers
📌 Violin & Scatter plots — analyze relationships between interest rate, FICO scores, installments & loan status
📌 Mutual Information & Random Forest importance — identify top risk-driving features

## 🧠 Modeling Approach

I trained and evaluated two classification models

| Model               | AUC Score |
|---------------------|-----------|
| Logistic Regression | 0.89      |
| Random Forest       | 0.89      |

## 📌 Key Insights from the Analysis

🔺 Higher interest rates are strongly linked to loan default
🔻 Lower FICO scores (both min and max ranges) indicate higher default probability
🧾 Variables like recoveries & collection_recovery_fee show skewness but correlate strongly with default loans
➖ Installment amount shows weak predictive power

📊 Both Mutual Information and Random Forest consistently highlight:
int_rate, fico_range_low, recoveries as top predictors of credit risk



##  🧰 Tech Stack

Python 3

pandas, NumPy — data manipulation

Matplotlib, Seaborn — data visualization

scikit-learn — modeling & evaluation

Jupyter Notebook (or other Python IDE / environment)

## 📂 Repository Structure

| File / Folder | Description |
 |--------------|-------------|
| /dataset/ | Raw data (or link / instructions to download) |
| requirements.txt | Dependencies |
| CreditRisk_Assessment.ipynb | Main notebook for EDA, preprocessing, modeling & evaluation |
| README.md | Project documentation |

## 🧮 How Probability, Statistics & ML Work Together

| Component   | Role |
|-------------|------|
| Probability | Estimates likelihood of default events from historical outcomes |
| Statistics  | Interprets distributions, skewness, variance & correlations |
| ML Models   | Learns complex patterns to provide accurate predictions and feature rankings |

## 🚀 Future Improvements

🔹 Hyperparameter tuning using GridSearchCV
🔹 Boosting models (XGBoost, LightGBM) for performance comparison
🔹 Handling class imbalance using SMOTE
🔹 Deployment using Streamlit / Flask for live predictions

## 📬 Contact

 📧 [amaljithprakash7@gmail.com](https://amaljithprakash7@gmail.com)
