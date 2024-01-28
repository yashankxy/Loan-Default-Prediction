# Machine Learning

---

# Loan Default Prediction using Logistic Regression

## Overview
This project build a predictive model using Logistic Regression to forecast whether a borrower will default on a loan based on their income and loan amount. The model utilizes Python libraries like Pandas, Matplotlib, Seaborn, and Scikit-learn to explore, preprocess, train, and evaluate the model's performance.

## Table of Contents
1. [Project Objective](#project-objective)
2. [Dataset](#dataset)
3. [Usage](#usage)
4. [Code Structure](#code-structure)
5. [Results](#results)
6. [Interpreting Model Coefficients](#interpreting-model-coefficients)
7. [Conclusion](#conclusion)

## Project Objective
The primary goal is to create a predictive model to determine if a borrower is likely to default on a loan based on their income and loan amount. The project involves steps like data exploration, model training, evaluation, and interpreting the model's coefficients.

## Dataset
The dataset used in this project (`loan.csv`) contains three columns:
- **Income**: Annual income of borrowers.
- **Loan Amount**: The amount of money borrowed.
- **Default**: Indicates whether the borrower defaulted or not.

## Usage
1. **Data Collection**: The dataset (`loan.csv`) needs to be placed in the project directory.
2. **Running the Code**: Execute the Python script or notebook to perform the following tasks:
    - Import and explore the data.
    - Prepare the data for model training.
    - Train and evaluate the Logistic Regression model.
    - Interpret the coefficients of the model.

## Code Structure
The code structure follows the steps outlined below:
- **Data Collection and Exploration**: Importing data, exploring its structure, and visualizing relationships between variables using boxplots and scatterplots.
- **Data Preparation**: Splitting the data into training and test sets.
- **Model Training and Evaluation**: Utilizing Logistic Regression to train a predictive model and evaluating its performance using accuracy and confusion matrix.
- **Interpreting Model Coefficients**: Understanding the impact of income and loan amount on the likelihood of loan default based on the model's coefficients.

## Results
The trained Logistic Regression model achieved an accuracy of approximately 89% on the test dataset. It correctly predicted 8 out of 9 instances in the test set.

## Interpreting Model Coefficients
The model coefficients reveal:
- A \$1 increase in income reduces the odds of loan default by 64%.
- A \$1 increase in the loan amount increases the odds of loan default by 16%.

## Conclusion
This project demonstrates the use of Logistic Regression for loan default prediction based on income and loan amount. It highlights the importance of model interpretation in understanding how independent variables influence the likelihood of a specific outcome.

---
