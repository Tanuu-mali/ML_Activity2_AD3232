# Activity 2: House Price Prediction Using Linear Regression

## 1. Project Overview
This project implements a **Linear Regression model** to predict house prices using the California Housing Dataset.

The objective is to understand supervised learning and apply a regression algorithm to predict continuous numerical values.

## 2. Dataset Description
- **Dataset Name:** California Housing Dataset
- **Source:** Scikit-learn
- **Dataset Link:** https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html
- **Total Records:** 20,640
- **Total Columns:** 9 (8 input features and 1 target variable)

### Selected Variables
- **Independent Variable (X):** MedInc (Median Income)
- **Dependent Variable (y):** MedHouseVal (Median House Value)

*Note: The target variable is measured in units of $100,000.*

## 3. Technologies and Libraries Used
- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 4. Methodology
The following steps were performed:

1. Imported the required Python libraries.
2. Loaded the California Housing Dataset.
3. Inspected the dataset using head(), info(), and describe().
4. Checked for missing values and duplicate records.
5. Selected the independent and dependent variables.
6. Visualized the relationship between median income and house prices using a scatter plot.
7. Split the dataset into 80% training data and 20% testing data.
8. Trained a Linear Regression model.
9. Calculated the model coefficient and intercept.
10. Predicted house prices using the trained model.
11. Evaluated the model using regression performance metrics.
12. Visualized actual and predicted values.
13. Predicted the house price for a new example.

## 5. Model Evaluation
The model was evaluated using the following metrics:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted values.
- **MSE (Mean Squared Error):** Measures the average squared difference between actual and predicted values.
- **R² Score:** Measures how well the model explains the variation in the target variable.

The actual evaluation scores are displayed when the notebook is executed.

## 6. Expected Outputs
- Dataset information and statistical summary
- Missing values and duplicate records
- Scatter plot of median income versus house value
- Linear Regression coefficient and intercept
- Regression equation
- Actual versus predicted values
- MAE, MSE, and R² score
- Actual vs. predicted visualization
- Prediction for a new input

## 7. How to Run the Project
1. Clone or download this repository.
2. Open the Jupyter Notebook (`.ipynb`) in Google Colab or Jupyter Notebook.
3. Run all cells sequentially.
4. Observe the model predictions, evaluation metrics, and visualizations.

## 8. Conclusion
This project demonstrates how Linear Regression can be used for house price prediction. The model learns the relationship between median income and median house value and uses this relationship to make predictions.

Through this activity, we gained practical understanding of supervised learning, data preprocessing, model training, prediction, and regression evaluation metrics.
