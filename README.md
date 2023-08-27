Treue_Technologies-Task3-Startups_Success_Rate_Prediction

    This repository contains code for predicting the success rate of startups using data analysis and machine learning techniques. The code is written in Python and uses libraries such as NumPy, pandas, matplotlib, seaborn, and scikit-learn.

Introduction
    
    Startup success prediction is an important task in the business world. This project aims to analyze a dataset containing information about startups and predict their success rates using machine learning models. The code performs data preprocessing, feature selection, correlation analysis, and model building.

Data Preprocessing and Exploration

    Load the startup dataset using pd.read_csv.
    Drop unnecessary columns to focus on relevant features.
    Handle missing values by dropping rows with missing data.
    Analyze data shape, information, and summary statistics.
    
Feature Selection and Correlation Analysis

    Select columns of interest based on domain knowledge.
    Calculate the correlation matrix to identify relationships between features.
    Visualize the correlation matrix using a heatmap.

Model Building

    Select relevant features as input and the target variable for prediction.
    Split the dataset into training and validation sets.
    Train a Decision Tree model and a Random Forest model using scikit-learn.
    Evaluate the models' accuracy and performance using classification reports.
    
Conclusion

    The analysis and model results indicate that the Random Forest model outperforms the Decision Tree model in predicting startup success rates. The Random Forest model's higher accuracy, precision, recall, and F1-score make it a more reliable choice for this prediction task.


