# Customer Spending Behavior Analysis

## Overview

This project focuses on predicting and analyzing customer spending behaviors at a supermarket. Using a dataset that captures various aspects of sales transactions, this analysis identifies patterns in customer purchases and predicts whether transactions are above or below average spending. The primary goal is to assist in developing personalized marketing strategies and improving customer segmentation.

## Dataset

The dataset, named `supermarket_sales - Sheet1.csv`, includes transaction details such as invoice ID, branch, city, customer type, gender, product line, unit price, quantity, tax, total, date, time, payment method, cost of goods sold (COGS), gross margin percentage, gross income, and customer ratings.

## Features

- **Data Preprocessing**: Checking for missing values and ensuring data quality.
- **Feature Engineering**: Generating new features like 'Above_Average' to classify transactions based on the average transaction value.
- **Model Building**: Employing different machine learning models such as Logistic Regression, Decision Tree, Linear Regression, and Random Forest to predict customer spending behaviors.
- **Model Evaluation**: Assessing models based on accuracy, precision, recall, and F1-score.

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## File Descriptions

- `README.md`: Provides an overview of the project and setup instructions.
- `customer_behavior_analysis.ipynb`: Jupyter notebook containing the code and documentation for the project.

## Results

The project successfully identifies key patterns in customer spending and segments customers based on transaction value, which aids in tailoring marketing efforts effectively.

## Usage

To run this project:
1. Ensure you have Python installed on your machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Execute the notebook `customer_behavior_analysis.ipynb` to view the analysis and results.

## Contribution

Contributions to this project are welcome. Please ensure to follow the best practices for code format and commits.
