# Student Performance Linear Regression

A beginner-friendly machine learning project focused on exploratory data analysis and linear regression using a student performance dataset.

## Project Goal

The goal of this project is to understand which factors have the strongest relationship with student performance and build a linear regression model to predict the Performance Index.

## Dataset

The dataset contains the following features:

- Hours Studied
- Previous Scores
- Extracurricular Activities
- Sleep Hours
- Sample Question Papers Practiced

Target:

- Performance Index

## Exploratory Data Analysis

The project includes:

- Missing value checks
- Duplicate removal
- Descriptive statistics
- Histograms
- Boxplots
- Scatterplots
- Correlation analysis
- Seaborn visualizations

One of the main findings from the EDA was that **Previous Scores had by far the strongest correlation with Performance Index**, while the other features had weaker relationships.

## Model

A Linear Regression model from Scikit-learn was trained using the available features.

Categorical values such as Extracurricular Activities were encoded before training.

## Model Performance

The model achieved approximately:

- MAE: 1.65
- MSE: 4.31
- RMSE: 2.08
- R²: 0.988

The high R² score indicates that the model explains a very large portion of the variation in student performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Main Takeaways

This project helped me practice:

- Exploratory Data Analysis
- Data visualization
- Correlation analysis
- Data preprocessing
- Linear Regression
- Model evaluation
- Residual analysis

## Files

- `main.ipynb` — Complete analysis and machine learning workflow
- `Student_Performance.csv` — Dataset used in the project