# diabetes-prediction-ml
A machine learning project for predicting diabetes using Python and scikit-learn.
Diabetes Prediction using Machine Learning
Project Overview
This project applies data science and machine learning techniques to predict whether a person has diabetes based on several health and lifestyle indicators.

The dataset contains medical attributes such as age, BMI, HbA1c level, blood glucose level, and smoking history. The goal of the analysis is to build a predictive model that can help identify individuals at high risk of diabetes, which could be useful in preventive healthcare.
Key Steps
1.Data Cleaning & Preprocessing
Removed duplicate rows and verified non-null values.
Encoded categorical variables (gender, smoking_history).
Scaled numerical features using MinMaxScaler for uniformity.

2.Exploratory Data Analysis (EDA)
Visualized the distributions of key health metrics.
Investigated relationships between diabetes and factors such as gender, age, and HbA1c levels.
Created derived features like age_category and HbA1c_level_category.

3.Balancing the Dataset
Used SMOTE (Synthetic Minority Oversampling Technique) to address class imbalance between diabetic and non-diabetic classes.

4.Model Building
Trained a Logistic Regression model to classify diabetes status.
Split dataset into training and testing subsets (80/20).

5.Model Evaluation
Evaluated performance using accuracy, precision, recall, F1-score, ROC–AUC score, and confusion matrix.

Tools and Libraries Used
Python
pandas, numpy — for data manipulation
matplotlib, seaborn — for visualization
scikit-learn — for preprocessing, SMOTE, modeling, and evaluation

Results
Balanced dataset size: 175,328 samples
Achieved strong model performance (you’ll fill in your metrics after running evaluations).
HbA1c level and blood glucose were the most predictive features.

How to Run
1.Clone the repository
git clone https://github.com/yishai-git/diabetes-prediction-ml.git
cd diabetes-prediction-ml
2.Install dependencies
pip install -r requirements.txt
3.Open the Jupyter Notebook
jupyter notebook diabetes_prediction.ipynb

Author
Jesse Ezeugwu
📍 Redeemer’s University, Osun State, Nigeria
🎓 Statistics and Data Science Student
Linkedin:www.linkedin.com/in/jesse-ezeugwu-03829431a
