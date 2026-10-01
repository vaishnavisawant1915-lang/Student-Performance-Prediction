# Student Performance Prediction Using Machine Learning

## Project Overview

This project focuses on predicting student academic performance using Machine Learning techniques. The study uses student habits, behavioral factors, and academic-related features to predict examination scores.

## Objectives

- Analyze factors affecting student academic performance.
- Perform data preprocessing and exploratory data analysis.
- Apply and compare multiple Machine Learning models.
- Optimize the selected models using hyperparameter tuning.
- Evaluate model performance using MAE, RMSE, R², and MAPE.
- Use SHAP for model explainability and feature importance analysis.

## Dataset

The dataset contains 1000 student records and includes features related to:

- Study hours per day
- Social media usage
- Netflix usage
- Attendance percentage
- Sleep hours
- Exercise frequency
- Mental health rating
- Diet quality
- Parental education level
- Internet quality
- Extracurricular participation

The target variable is `exam_score`.

## Machine Learning Models

The project compares:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Extra Trees
- XGBoost

## Evaluation Metrics

The models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Mean Absolute Percentage Error (MAPE)

## Explainability

SHAP (SHapley Additive exPlanations) is used to understand model predictions and identify the features that contribute most to predicted student performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SHAP
- Jupyter Notebook / Google Colab

## Project Files

- `Student_Performance.ipynb` – Complete Machine Learning notebook
- `student_habits_performance_for RM.csv` – Dataset
- `Student_Performance_Prediction_Research_Report.pdf` – Research report

## Conclusion

The project demonstrates how Machine Learning can be applied to student performance prediction and how explainable AI techniques can help understand the factors influencing model predictions.
