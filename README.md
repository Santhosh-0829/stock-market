# Stock Price Analysis and Prediction

This repository contains a Python notebook for analyzing historical stock data and building a simple model to predict stock price movements.

## Project Overview

The project performs the following steps:

1.  **Data Loading and Exploration:** Loads stock data from a CSV file and performs initial data exploration, including checking data types, missing values, and basic statistics.
2.  **Data Preprocessing:** Converts the 'date' column to datetime objects and creates a target variable indicating whether the stock price increased the next day.
3.  **Data Visualization:** Generates plots to visualize stock price trends and trading volumes for selected companies.
4.  **Model Training:** Splits the data into training and testing sets and trains a Logistic Regression model to predict the next day's stock price movement.
5.  **Model Evaluation:** Evaluates the model's performance using accuracy score and a confusion matrix.

## Data

The project uses the `all_stocks_5yr.csv` file, which should be placed in the `/content/drive/MyDrive/` directory if running in Google Colab, or in a suitable data directory within your project if running locally.

## Dependencies

The following Python libraries are required:

*   pandas
*   matplotlib
*   numpy
*   tensorflow (though not explicitly used in the provided code snippets, it's imported)
*   keras (though not explicitly used in the provided code snippets, it's imported)
*   seaborn
*   scikit-learn

You can install the dependencies using pip:

## Usage

1.  Ensure you have the required data file (`all_stocks_5yr.csv`) in the correct location.
2.  Open the notebook in Google Colab or a Jupyter environment.
3.  Run the code cells sequentially to execute the analysis and model training.

## Files

*   `your_notebook_name.ipynb`: The main notebook containing the code for stock analysis and prediction.
*   `all_stocks_5yr.csv`: The dataset used in this project.
