# 🏡 House Price Prediction – Advanced

**PRCP-1020 | Data Science & Machine Learning Capstone Project**

## 📌 Project Overview

This project focuses on developing a machine learning-based house price prediction system using the Ames Housing Dataset. It uses property characteristics to estimate residential house prices through regression algorithms.

The project demonstrates the complete machine learning workflow, from data exploration and preprocessing to model training, evaluation, and prediction.

## 🎯 Project Objectives

- Understand and analyze residential housing data.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values and categorical variables.
- Build and compare multiple regression models.
- Evaluate model performance using appropriate metrics.
- Identify important features influencing house price predictions.

## 📊 Dataset Description

The project uses the Ames Housing Dataset, containing 1,460 records and 81 columns.

It includes property-related information such as:
- Living area
- Overall quality
- Number of bedrooms and bathrooms
- Neighbourhood
- Garage and basement features
- Sale price

**Target Variable:** `SalePrice`

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🤖 Machine Learning Algorithms

Four regression algorithms were implemented:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor

## 📈 Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
- 5-Fold Cross-Validation

Additional analysis includes feature importance, actual vs predicted price comparison, and residual analysis.

## 📂 Project Structure

```text
House-Price-Prediction-PRCP1020-Aditi/
│
└── Data/
    ├── data.csv
    ├── house prices.docx
    └── notebooks/
        └── PRCP-1020_House_Price_Prediction_Advanced.ipynb
```

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

   `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`

3. Open the Jupyter Notebook located inside `Data/notebooks/`.
4. Run the notebook cells sequentially.

## ⚠️ Limitations

The model is trained on historical housing data from Ames, Iowa. Its predictions may not accurately represent current property prices or real estate markets in other locations.

## 🚀 Future Scope

- Experiment with advanced algorithms such as XGBoost and LightGBM.
- Perform hyperparameter optimization.
- Develop an interactive house price prediction application.
- Incorporate more recent real estate datasets.

## 👩‍💻 Author

**Aditi Kumari**

Data Science & Machine Learning Project

---

*This project was developed as part of the DataMites Data Science Capstone Project – PRCP-1020.*
