# Medical Insurance Cost Prediction

## Project Overview

This project focuses on predicting individual medical insurance charges using Machine Learning regression algorithms.

The goal is to analyze different features affecting insurance costs and compare the performance of multiple regression models.

## Dataset

- Dataset: Medical Insurance Cost Dataset
- Target Variable: `charges`
- Features:
  - age
  - sex
  - bmi
  - children
  - smoker
  - region

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Models

1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. ElasticNet Regression

## Methodology

1. Data Loading and Inspection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Categorical Feature Encoding
5. Feature Scaling using StandardScaler
6. Train-Test Split
7. Model Training and Evaluation
8. 5-Fold Cross Validation

## Model Performance

Best Cross-Validation Model: Ridge Regression

- CV R² Score: 0.7424
- CV RMSE: 6106.42

The Ridge Regression model explains approximately 74.24% of the variance in insurance charges based on cross-validation.

## Project Structure

```text
Medical-Insurance-Cost-Prediction/
│
├── Insurance_Cost_Prediction.ipynb
├── README.md
├── requirements.txt
├── .gitignore
│
└── results/
    ├── model_comparison.png
    └── cross_validation.png
```

## Future Improvements

- Polynomial Regression
- Feature Engineering
- Hyperparameter Tuning
- Additional Regression Algorithms

## Author

S.M. ALi Ahadul Hassan Himel

## Acknowledgment

This project was developed for educational purposes to improve practical understanding of Machine Learning and Regression Algorithms.
