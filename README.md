# Data Science Midterm Project by Mehran Bhzadi & Krishna Purani
## Project/Goals
The goal of this project is to build a machine learning pipeline to predict housing prices using historical housing sales data. The project involved data preprocessing, exploratory data analysis (EDA), model selection, hyperparameter tuning, and the construction of a final pipeline for predicting housing prices.

## Process
Step 1: Load Data - Load the housing sales data from the provided JSON files into a Pandas dataframe.
Step 2: Explore and Clean Data - Perform EDA to understand the distribution of variables and identify any outliers.
Step 3: Model Selection and Evaluation - Try various supervised learning models to determine the performance of each model.
Step 4: Tuning and Pipelines 

## Results
- Decided to use  Random Forest as it had the lowest Mean Absolute Error of 0.050528.
- High Importance Features that determine the house price are lot_sqft (0.1235), price_per_sqft (0.1220), sold_year (0.0753), sqft (0.0741), baths: (0.0712) 
Scaled features such as lot_sqft_scaled, sqft_scaled, baths_scaled, and stories_scaled have very low importance, indicating that these features do not contribute much to the model's decision-making process.
- 

## Challenges 
1. Data cleaning: The raw data had missing values and inconsistencies that required careful handling.
2. Feature selection: Identifying which features were most relevant to housing prices was tricky, as many variables had complex relationships.

## Future Goals
Implementing a more detailed feature selection process to remove redundant features and improve the model's interpretability and then deploying the final model as a web application for users to input housing data and receive predictions on housing prices.

