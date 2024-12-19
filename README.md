# Football Match Prediction

This project focuses on predicting the results of football matches using a Random Forest classifier. It processes historical match data, calculates rolling averages, and applies machine learning techniques to estimate outcomes.

## Features

- **Data Processing**: Cleans and preprocesses data, including type conversions and rolling averages.
- **Random Forest Model**: Implements a classifier to predict match results based on key metrics.
- **Evaluation**: Assesses model performance using metrics like accuracy and precision.
- **Data Merging**: Combines predictions for both home and away teams for enhanced insights.

## How It Works

1. **Data Preparation**:
   - Loads historical match data.
   - Converts necessary columns to appropriate data types.
   - Calculates rolling averages for specified metrics.

2. **Model Training**:
   - Splits data into training and testing sets based on a date threshold.
   - Trains a Random Forest classifier using key predictors.

3. **Prediction and Evaluation**:
   - Makes predictions on the test dataset.
   - Evaluates model performance using metrics such as accuracy and precision.

4. **Insights**:
   - Merges predictions for both home and away teams.
   - Provides a detailed view of predicted versus actual results.

## Future Improvements

- Incorporate additional seasons and variables to enhance precision.
- Experiment with different hyperparameters and machine learning models.

---

This project is an exploration of machine learning techniques applied to sports analytics, showcasing the potential for data-driven insights in football match predictions.
