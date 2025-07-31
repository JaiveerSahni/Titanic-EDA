# 🛳️ Titanic Survival Prediction – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project explores the Titanic dataset from Kaggle using Exploratory Data Analysis (EDA) techniques. The goal is to identify key factors that influenced passenger survival during the tragic voyage. Using Python and its data science libraries, the notebook uncovers patterns and visual insights into survival trends.

---

## 📂 Dataset Description
The dataset includes various features such as:

- **PassengerId** – Unique ID for each passenger  
- **Survived** – Survival (0 = No, 1 = Yes)  
- **Pclass** – Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)  
- **Name, Sex, Age** – Demographic data  
- **SibSp, Parch** – Family aboard  
- **Ticket, Fare** – Fare details  
- **Cabin** – Cabin number  
- **Embarked** – Port of embarkation

---
 ## 📌 Libraries Used

- `pandas` – data manipulation  
- `numpy` – numerical computations  
- `matplotlib` & `seaborn` – data visualization  

---

## 📊 Key Analyses Performed

### ✅ Univariate Analysis
- Distribution of Age and Fare
- Passenger class and gender counts
- Overall survival distribution

### ✅ Bivariate Analysis
- Survival rate by **Pclass**, **Sex**, and **Embarked**
- Fare distributions by class
- Age distributions by survival status

### ✅ Multivariate Analysis
- Heatmap of correlations between numerical features
- Crosstabs of categorical variables

---

## 🔍 Key Insights
- **Females** had a much higher survival rate than males.
- Passengers from **1st class** were more likely to survive than those in 2nd or 3rd.
- Survivors tended to be younger and paid higher fares.
- Most no of passengers were travelling through Pclass 3 as it was the cheapest  
- Embarkation point (Cherbourg) had a slightly higher survival rate.

---
## 💡 Next Steps & Improvements
- Feature engineering (e.g., extract title from names)
- Build classification models (e.g., Logistic Regression, Decision Tree)
- Evaluate models using accuracy, confusion matrix, and ROC-AUC
- Deploy a basic web app with model predictions

---
## 🚀 How to Run
1. Clone the repo:  
   ```bash
   git clone https://github.com/JaiveerSahni/Titanic-EDA.git
   
2.Open the notebook in Jupyter Notebook or Google Colab.
3.Run all cells to reproduce the analysis.

## 👤 Author
Jaiveer Singh Sahni
📧 LinkedIn



