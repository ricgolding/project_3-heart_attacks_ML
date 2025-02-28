# Heart Attack Prediction Project

# Project by
-Sandra
-Prince
-Carles
-Ricardo

## Overview
This project focuses on analyzing and predicting heart attack risks using machine learning techniques. The dataset is preprocessed to clean and prepare the data before applying predictive models.

## Dataset
The dataset used in this project contains various medical and demographic attributes related to heart health. It includes features such as:
- Blood pressure (systolic and diastolic)
- Age
- Cholesterol levels
- Heart rate
- Other relevant medical factors

## Data Preprocessing
Several preprocessing steps were performed to clean and prepare the dataset:
- Checking for missing values and handling them appropriately
- Standardizing column names for consistency
- Splitting the blood pressure column into systolic and diastolic pressures
- Dropping unnecessary columns such as `patient_id`, `continent`, and `hemisphere`
- Converting categorical variables and normalizing numerical features

## Exploratory Data Analysis (EDA)
EDA was performed using libraries such as Pandas, Matplotlib, and Seaborn to:
- Visualize the distribution of key medical attributes
- Identify correlations between different features
- Examine the relationship between heart attack risk and key medical indicators

## Machine Learning Model
A **Decision Tree Classifier** was used to predict heart attack risk based on the preprocessed dataset. The model was trained using:
- Feature engineering to optimize input variables
- Model evaluation metrics to assess performance
- Decision tree visualization to understand important contributing factors

## Results
The project provides insights into key factors influencing heart attack risks and demonstrates the effectiveness of machine learning models in medical diagnosis. The results can be used to improve early detection and preventive measures.

## Requirements
To run this notebook, install the following dependencies:
```bash
pip install -e .
```

## Usage
1. Load the dataset.
2. Run the preprocessing steps.
3. Perform EDA to understand the data.
4. Train and evaluate the decision tree model.
5. Visualize important features contributing to heart attack risks.

## Conclusion
This project highlights the importance of data-driven approaches in medical predictions. Further improvements can be made by exploring other machine learning models and fine-tuning hyperparameters for better accuracy.

