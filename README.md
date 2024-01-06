# Housing Price Prediction with PySpark

This project demonstrates the use of PySpark, a Python library for Apache Spark, to build a linear regression model for predicting housing prices. The dataset used in this project contains various features such as geographical coordinates, housing age, room count, and income, among others.

## Overview
The project consists of the following main steps:

1. Data Preprocessing:

- Standardization of numerical features using StandardScaler.
- Indexing and encoding categorical features using StringIndexer and OneHotEncoder.
- Assembling the features into a single vector using VectorAssembler.

2. Linear Regression Model:

- Training a linear regression model using LinearRegression from PySpark's MLlib.
-  Generating predictions on the training dataset.

3. Model Evaluation:

- Evaluating the model using metrics such as Mean Squared Error, Root Mean Squared Error, Mean Absolute Error, and R-squared.

## Code Structure
The code is structured as follows:

1. Loading and Exploring Data: Loading the dataset and, Displaying sample records and summary statistics.

2. Feature Scaling: Standardizing numerical features.

3. Categorical Feature Encoding: Indexing and encoding categorical features.

4. Assembling Feature Vector: Combining standardized numerical features and one-hot encoded categorical features into a final feature vector.

5. Linear Regression Model: Building and training a linear regression model.

6. Model Evaluation: Evaluating the model performance using regression metrics.

7. Predictions: Generating predictions on both the training and test datasets.

## Requirements
1. PySpark
2. Python 3.x
3. Jupyter Notebook (for interactive execution)

## How to Use

1. Clone the repository:

- git clone https://github.com/your-username/housing-price-prediction-pyspark.git
- cd housing-price-prediction-pyspark

2. Install the required dependencies:

- pip install -r requirements.txt

3. Run the Jupyter Notebook:

- Open the notebook housing_price_prediction_pyspark.ipynb and execute the cells.

## Results
After running the notebook, you should see the model's predictions and evaluation metrics. The key metrics include Mean Squared Error, Root Mean Squared Error, Mean Absolute Error, and R-squared.

## Future Work
This project can be extended by:

- Exploring different regression models.
- Tuning hyperparameters for better model performance.
- Visualizing the predictions and residuals for a deeper understanding.







