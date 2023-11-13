# Flight Fare Prediction Data Science Project

## Overview
This GitHub repository contains the code and documentation for the Flight Fare Prediction data science project. The goal of this project is to predict flight ticket prices using machine learning techniques. This information can be valuable for both airlines to set competitive prices and travelers to plan their trips effectively.

## Project Structure
The project is organized into the following sections:

### 1. Pre-Data Analysis Report
   - **Problem Statement**
   - **Objectives**
   - **Dataset Overview**

### 2. Data Exploration
   - **Univariate Analysis**
   - **Bivariate Analysis**
   - **Insights from Domain Analysis**

### 3. Data Preprocessing
   - **Handling missing values**
   - **Outlier detection and treatment**
   - **Feature engineering**
   - **Data scaling**

### 4. Model Selection
   - **Considered models:**
      - Linear Regression
      - Random Forest Regressor
      - Gradient Boosting Regressor
   - **Model evaluation metrics:**
      - Mean Absolute Error (MAE)
      - Mean Squared Error (MSE)
      - Root Mean Squared Error (RMSE)

### 5. Model Training and Evaluation
   - **Train-test split**
   - **Fitting Random Forest Regressor**
   - **Hyperparameter tuning using RandomizedSearchCV**
   - **Model evaluation and comparison**

### 6. Challenges Faced
   - **Overfitting**
   - **Data Preprocessing challenges**
   - **Hyperparameter Tuning complexity**
   - **Evaluation Metrics selection**
   - **Data Quality issues**

### 7. Next Steps
   - **Final steps in the project**
   - **Model deployment considerations**
   - **Recommendations for further refinement**

## How to Use This Repository
- The `code` directory contains all the Python scripts used for data analysis, preprocessing, model training, and evaluation.
- The `data` directory stores the dataset used in the project.
- The `notebooks` directory includes Jupyter notebooks corresponding to each major step in the project.
- The `reports` directory contains detailed reports, including the pre-data analysis report, model comparison report, and challenges faced during the project.

## Getting Started
1. **Clone the repository:** `git clone [repository_url]`
2. **Install the required dependencies:** `pip install -r requirements.txt`
3. **Execute the Jupyter notebooks** in the `notebooks` directory in sequential order to understand the project workflow.

## Conclusion
This project aims to provide insights into flight fare prediction and offers a predictive model recommendation based on extensive analysis and evaluation. The Random Forest Regressor, after hyperparameter tuning, is suggested for production use. Further refinement and validation on real-world data are recommended before deployment.
