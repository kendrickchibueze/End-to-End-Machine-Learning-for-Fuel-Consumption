# End-to-End-Machine-Learning-For-Fuel-Consumption 🎗

## Overview
This project aims to predict the **Miles Per Gallon (MPG)** of vehicles based on various vehicle attributes like displacement, weight, acceleration, and others. The dataset contains information from the 1970s and 1980s. The primary goal is to create a predictive model for vehicle fuel efficiency.

## Steps Taken

### 1. Data Exploration and Analysis
- **Check Data Types:** Explored the data types of each column.
- **Null Values:** Checked for and handled missing values in the dataset.
- **Outliers:** Identified and dealt with outliers that might affect model performance.
- **Correlation:** Examined the correlation matrix with respect to the target variable (MPG).
- **Feature Engineering:** Created new features such as:
  - Displacement on Power
  - Weight on Cylinder
  - Acceleration on Power
  - Acceleration on Cylinder

### 2. Data Preparation
- **Handling Categorical Data:** Used **OneHotEncoder** to encode categorical variables.
- **Missing Value Imputation:** Applied **SimpleImputer** to fill in missing values.
- **Feature Addition:** Engineered new features using custom transformations.
- **Data Transformation Pipeline:** Built a pipeline to process numerical and categorical columns.

### 3. Model Selection and Training
- **Algorithms Used:**
  - **Linear Regression**
  - **Decision Tree**
  - **Random Forest**
- **Model Evaluation:**
  - Evaluated models using **Mean Squared Error (MSE)**.
  - Used **Cross Validation** to assess the models' generalizability.

### 4. Model Optimization
- **Hyperparameter Tuning:** Applied **GridSearchCV** for tuning model parameters.
- **Feature Importance:** Analyzed the importance of features in making predictions.

### 5. Final Evaluation
- **Test Data Evaluation:** Assessed the model's performance on a separate test set.
- **Model Saving:** The trained model was saved for future use.

## Conclusion
The project successfully developed a model to predict the MPG value of vehicles based on multiple vehicle attributes. The final model demonstrated good performance in predicting fuel efficiency.

## Future Work
- Experiment with additional feature engineering.
- Explore more advanced algorithms for potential performance improvements.
- Test the model with more recent vehicle data.

