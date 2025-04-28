# 🚢 Titanic Survival Analysis (EDA Project)

## 📋 Project Description

This project performs **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset** from Kaggle.  
The goal is to uncover patterns, trends, and important features that influence passenger survival during the Titanic disaster.

We explore the data using:
- Basic statistics (`.describe()`, `.info()`, `.value_counts()`)
- Data visualizations (`sns.pairplot()`, `sns.heatmap()`, histograms, boxplots, scatterplots)
- Observations and interpretations for each plot
- Summary of key findings

---

## 📊 Techniques Used

- Pandas for data exploration
- Seaborn and Matplotlib for visualizations
- Correlation analysis
- Feature-wise survival analysis (Sex, Pclass, Fare, Age, Family, Cabin)

---

## 🔍 Key Insights

| Aspect | Observation |
| :--- | :--- |
| **Sex** | Females had higher survival rates. |
| **Pclass** | 1st class passengers had better survival odds. |
| **Fare** | Higher fares correlated with higher survival. |
| **Age** | Younger passengers (especially children) slightly more likely to survive. |
| **Family (SibSp, Parch)** | Small families had a slight survival advantage. |
| **Cabin Info** | Missing cabin data common; having a cabin number often linked to higher survival chances. |

---

## 📂 Files

- `train.csv` - Training dataset (with survival labels)
- `test.csv` - Testing dataset (without survival labels)
- `gender_submission.csv` - Sample submission format
- `Titanic_EDA.ipynb` - Jupyter Notebook with full EDA

---

## 🚀 Future Work

- Handle missing data with imputation techniques.
- Feature engineering for better model performance.
- Build predictive models (Logistic Regression, Random Forest, etc.).
- Submit predictions to Kaggle!

---

## 🏷️ Tags

`EDA` `Titanic Dataset` `Kaggle` `Data Visualization` `Data Analysis` `Machine Learning`
