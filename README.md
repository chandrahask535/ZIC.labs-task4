# ZIC.labs-TASK4

# SALES PREDICTION USING PYTHON

## Author: CHANDRAHAS K

## Batch: NOVEMBER

## Domain: Data Science

# Aim: 
Sales prediction involving forecasting the amount of a product that customers will purchase, taking into account with various factors such as advertising expenditure, target audience segmentation, and advertising platform selection.

## Datasets

The following datasets were used for this project:
advertising.xls: The advertising dataset contains the information about the relationship between 'TV','Radio', 'Newspaper' and 'sales'.

## Libraries Used

The following important libraries were used for this project:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn.model_selection.train_test_split
- sklearn.linear_model.LinearRegression
- sklearn.metrics.mean_squared_error
- sklearn.metrics.mean_absolute_error
- sklearn.metrics.r2_score

  ## DATA ANALYSIS

  1. To read the first 5 lines of the datas set `df.head()` was used.
  2. Descriptive statistics for the dataset were displayed using `df.describe()`.
  3. Missing values in the dataset were checked using `df.isna().sum()`.
  4. To check number of columns and rows in the dataframes `df.shape`.
  5. information about the `df.info()`

  ## DATA VISUALISATION
  
     1. To Create a pair plot `sns.pairplot(df)` and `plt.show()` was used.
     2. To create a Correlation heatmap `df.corr()`,`plt.title('Correlation Heatmap')`and `plt.show()`          were used required preferences.

  ## Model Training and Evaluation

  1. Model Training:
     
      A Linear Regression model is trained using the `LinearRegression` class from scikit-learn.
      The model is fitted on the training data (`X_train` and `y_train`).

  2. Model Evaluation:
     
        Predictions are made on the test set (`X_test`), and key regression metrics are calculated:
            Mean Squared Error (MSE)
            Mean Absolute Error (MAE)
            R-squared (R2)
    -The actual vs. predicted values are visualized with a scatter plot.
    -Predictions are saved to a CSV file named `sales_prediction.csv`.
