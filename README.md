Student Performance Prediction 🎓📊
Project Overview
This project predicts student final grades (G3) based on various academic and personal features using machine learning. The dataset includes information about student demographics, past grades (G1, G2), study habits, family background, and other factors influencing performance.
The goal is to build a Random Forest regression model that can predict final grades and provide insights into key factors affecting student performance.

Dataset-
-Source: UCI Student Performance Dataset ,
-Features include: school, sex, age, studytime, failures, G1, G2, absences, etc. ,
-Target variable: G3 (final grade, 0–20) ,

Tools & Libraries
-Python: pandas, NumPy, Matplotlib, Seaborn ,
-Machine Learning: scikit-learn (Random Forest Regressor, RandomizedSearchCV, train-test split) ,
-Model Saving: joblib ,

Project Steps
1.Exploratory Data Analysis (EDA)
-Explored dataset structure, types, missing values, and duplicates ,
-Visualized numerical and categorical features ,
-Created correlation matrix to identify important features ,
2.Data Preprocessing
-Encoded binary categorical features using Label Encoding ,
-Removed less useful features to improve model performance ,
3.Feature Selection
-Selected features most correlated with the target variable (G3) ,
4.Modeling
-Trained Random Forest Regressor ,
-Hyperparameter tuning using RandomizedSearchCV ,
5.Model Evaluation
-Metrics: R² score and RMSE ,
-Visualizations: 
--Residual Plot ,
--Feature Importance Plot ,
6.Model Deployment
-Trained model saved using joblib for future predictions ,

Results
-Achieved R² score of ~0.8 on test data ,
-Top features influencing grades: G1, G2, studytime, failures ,
-Residual plot shows errors are randomly distributed → good model fit 
