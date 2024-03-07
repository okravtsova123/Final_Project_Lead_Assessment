# Final_Project_Lead_Assessment

# LEAD QUALITY ASSESSMENT FOR ONLINE PURCHASING: ML prediction model & EDA 

## Description
This project focuses on predicting whether online visitors will convert into customers based on their behavior and interactions with the website. Leveraging the "Online Shoppers Purchasing Intention Dataset" we aim to develop predictive models that can identify potential customers, allowing businesses to optimize marketing strategies and improve conversion rates.

By analyzing features such as pages visited, duration spent on informational pages, product-related pages, bounce rates, and more, our goal is to build robust models that provide actionable insights into users' purchase intentions. This predictive approach enables businesses to make informed decisions, tailor their online strategies, and enhance the overall user experience to drive successful customer conversions.

the 2nd part is dedicated to EDA which can provide insights into marketing strategy optimization and sales process optimization, by providing clear understanding of conversion rates dependancy on the variables describing a lead or company's action for conversion.

## Dataset Information
- The dataset used for this project is the "Online Shoppers Purchasing Intention Dataset" from Kaggle, 100k rows
- It includes features such as administrative pages visited, duration spent on informational pages, product-related pages, bounce rates, and more.
- The target variable is 'Revenue,' indicating whether a visitor made a purchase (1 for Yes, 0 for No).

## Data Exploration and cleaning data
- Explore the dataset to understand the distribution of features and the target variable.
- Clean the data Remove typos, Correct datatypes

## Feature Engineering
- Perform any necessary preprocessing steps, such as handling missing values or outliers.
- Encode variables
- Use downsampling and upsamling techniques for balancing the data within training set

## Model Selection
- Split the data into training and testing sets.
- Applying machine learning algorithms for binary classification.
- Train the selected models on the training set.


## Model Evaluation
- Evaluate the models using relevant metrics (accuracy, precision, recall, F1 score).
- Use cross-validation to ensure robustness.
- Fine-tune hyperparameters for better performance.
- Choose appropriate machine learning algorithms by comparing logistic regression, decision trees, random forests and KNN models

The model is chosen based on Recall error as the price of the mistake for FN is higher than for FP for the particular case with subscription model product. Business solution for handling the FP is provided within the presentation.

## Add User Input Interface 
- Include input part for end user to input some variables and get the prediction of whether online visitors will convert into customers or not.