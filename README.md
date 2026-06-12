# House-Price-Prediction
Developed a machine learning model to predict house prices using the California Housing Dataset. Performed end-to-end data analysis, preprocessing, feature engineering, model selection, hyperparameter tuning, and model evaluation to improve prediction accuracy.


## Resume Project Explanation

### House Price Prediction using Machine Learning

**Project Title:** House Price Prediction using Machine Learning

**Tools & Technologies:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, GridSearchCV

**Project Description:**
Developed a machine learning model to predict house prices using the California Housing Dataset. Performed end-to-end data analysis, preprocessing, feature engineering, model selection, hyperparameter tuning, and model evaluation to improve prediction accuracy.

**Key Responsibilities:**

* Performed Exploratory Data Analysis (EDA) to understand data distribution and identify missing values.
* Handled missing values using imputation techniques.
* Built preprocessing pipelines using ColumnTransformer and Pipeline.
* Applied feature scaling and categorical encoding.
* Trained and compared multiple regression models:

  * Linear Regression
  * Ridge Regression
  * Lasso Regression
  * Random Forest Regressor
  * HistGradientBoosting Regressor
* Used K-Fold Cross Validation for robust model evaluation.
* Performed Hyperparameter Tuning using GridSearchCV.
* Evaluated models using RMSE, MAE, and R² Score.
* Developed an inference function for predicting house prices on new data.

**Results:**

* Best Model: HistGradientBoosting Regressor
* Cross Validation RMSE: 47,408
* Test RMSE: 47,170
* Test MAE: 30,948
* Test R² Score: 0.83

**Business Impact:**
The model can assist real estate companies, buyers, and sellers in estimating property prices accurately based on housing and location-related features.

---

# Interview Explanation (2-3 Minutes)

"I developed a House Price Prediction project using the California Housing dataset. The objective was to predict the median house value based on various housing features such as location, population, number of rooms, number of bedrooms, and median income.

I started with Exploratory Data Analysis to understand the dataset and identify missing values. I found missing values in the total_bedrooms feature and handled them using imputation.

For preprocessing, I used Scikit-Learn's Pipeline and ColumnTransformer to automate scaling, encoding, and data transformation steps. After preprocessing, I trained multiple regression models including Linear Regression, Ridge, Lasso, Random Forest, and HistGradientBoosting Regressor.

To select the best model, I applied K-Fold Cross Validation and compared RMSE scores. HistGradientBoosting performed the best, so I further optimized it using GridSearchCV for hyperparameter tuning.

The final tuned model achieved an R² score of 83% on test data with an RMSE of around 47,000. Finally, I created a prediction function that can estimate house prices for new property data."

---

# GitHub Project Description (README)

## House Price Prediction using Machine Learning

### Overview

This project predicts house prices using the California Housing Dataset and machine learning techniques. The project covers the complete machine learning lifecycle including data preprocessing, exploratory data analysis, model building, hyperparameter tuning, evaluation, and prediction.

### Dataset

California Housing Dataset containing features such as:

* Longitude
* Latitude
* Housing Median Age
* Total Rooms
* Total Bedrooms
* Population
* Households
* Median Income
* Ocean Proximity

### Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Missing Value Treatment
4. Feature Engineering
5. Data Preprocessing
6. Model Training
7. Cross Validation
8. Hyperparameter Tuning using GridSearchCV
9. Model Evaluation
10. Price Prediction

### Models Implemented

* Linear Regression
* Ridge Regression
* Lasso Regression
* Random Forest Regressor
* HistGradientBoosting Regressor

### Best Model Performance

| Metric        | Value  |
| ------------- | ------ |
| CV RMSE       | 47,408 |
| Test RMSE     | 47,170 |
| Test MAE      | 30,948 |
| Test R² Score | 0.83   |

### Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

### Key Learning Outcomes

* Regression Modeling
* Data Preprocessing Pipelines
* Cross Validation
* Hyperparameter Tuning
* Model Evaluation Metrics
* Production-ready ML Workflow

### Future Improvements

* Deploy model using Flask/FastAPI
* Create Streamlit Web Application
* Implement XGBoost and LightGBM
* Add Feature Importance Analysis

---

### Common Interview Question: Why did you choose HistGradientBoosting?

**Answer:**
"HistGradientBoosting can handle large datasets efficiently and capture non-linear relationships between features and target variables. During model comparison, it achieved the lowest RMSE score among all models, which is why I selected it as the final model and further optimized it using GridSearchCV."
