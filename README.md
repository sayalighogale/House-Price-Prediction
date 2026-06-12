# House-Price-Prediction
Developed a machine learning model to predict house prices using the California Housing Dataset. Performed end-to-end data analysis, preprocessing, feature engineering, model selection, hyperparameter tuning, and model evaluation to improve prediction accuracy.


## Resume Project Explanation

### House Price Prediction using Machine Learning

**Project Title:** House Price Prediction using Machine Learning

**Tools & Technologies:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, GridSearchCV

**Project Description:**
Developed a machine learning model to predict house prices using the California Housing Dataset. Performed end-to-end data analysis, preprocessing, feature engineering, model selection, hyperparameter tuning, and model evaluation to improve prediction accuracy.

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
