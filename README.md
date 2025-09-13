# Insurance-Premium-Prediction-using-Regresson
---
**Overview**

This project predicts insurance premiums using various regression algorithms.
The goal is to analyze how demographic and lifestyle features (such as age, BMI, smoking habits, and region) influence the insurance charges.

By comparing multiple regression models, we identify the best-performing algorithm for predicting insurance costs.

---
**Dataset**
Source: Kaggle - 
Rows: 1,338
Columns: 7
---
**Features**
age: Age of the individual
sex: Gender of the policyholder
bmi: Body Mass Index
children: Number of children/dependents covered by health insurance
smoker: Smoking status (yes/no)
region: Residential area in the US
charges: Medical insurance costs (Target variable)

---
**Technologies Used**
Python 3.x
Libraries:
pandas, numpy → Data manipulation
matplotlib, seaborn → Data visualization
scikit-learn → Machine learning models & evaluation

---
**Methodology**

1.Data Preprocessing
Handled categorical variables (sex, smoker, region) using encoding
Checked for missing values and outliers
Feature scaling where necessary

2.Exploratory Data Analysis (EDA)
Distribution plots for age, BMI, charges
Correlation heatmap
Smoking vs. non-smoking cost comparison

3.Modeling
Implemented and compared multiple regression algorithms:
Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor

4.Evaluation Metrics
R² Score
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)

---
**Results**

Best Model:  XGBoost (highest R², lowest RMSE)

---
**Project Structure**
Insurance-Premium-Prediction/
│── Insurance-Premium-Prediction-using-Regression-Algorithms.ipynb
│── README.md
│── requirements.txt
└── dataset/insurance.csv
---
**How to Run**
1.Clone this repository:
git clone https://github.com/yourusername/Insurance-Premium-Prediction.git
cd Insurance-Premium-Prediction

2.Install dependencies:
pip install -r requirements.txt

3.Run the notebook:
jupyter notebook Insurance-Premium-Prediction-using-Regression-Algorithms.ipynb

---
**Future Improvements**
Hyperparameter tuning with GridSearchCV/RandomizedSearchCV
Try advanced models like CatBoost, LightGBM
Deploy model with Streamlit or Flask
Build a simple insurance premium prediction web app
---
Author

Your Name- NirmalanSK

Email: nirmalkaja812@gmail.com

 LinkedIn:www.linkedin.com/in/nirmalansk

 GitHub:www.github.com/NirmalanSK
 ---
 If you like this project, don’t forget to ⭐ star the repo!
