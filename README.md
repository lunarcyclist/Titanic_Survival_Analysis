# Titanic_Survival_Analysis

## Project Overview
This project focuses on predicting passenger survival on the Titanic using machine learning techniques. The workflow includes data preprocessing, feature engineering, model training, evaluation, and visualization using Tableau. Multiple models were tested and fine-tuned for optimal performance.

## Libraries Used
- pandas & numpy for data manipulation and numerical computations
- matplotlib & seaborn for data visualization
- scikit-learn for machine learning models and preprocessing
- xgboost for advanced gradient boosting
- imbalanced-learn to handle imbalanced datasets
- Weights & Biases (W&B) for experiment tracking

## Data Preprocessing
- Handled missing values using median/mode imputation
- Encoded categorical variables (Sex, Embarked) using one-hot encoding
- Standardized numerical features for better model performance

## Feature Engineering
- Created new features like FamilySize and HasCabin
- Applied log transformation to Fare for normalization
- Removed irrelevant features to improve efficiency

## Model Training & Evaluation
- Trained Logistic Regression, SVM, Random Forest, and XGBoost models
- Used SMOTE to handle class imbalance
- Fine-tuned hyperparameters for improved accuracy
- Random Forest achieved the best accuracy of **84.45%**

## Visualization
- Tableau visualizations for survival rates by class, gender, and age
- Correlation matrix analysis to select important features

## Challenges & Solutions
- Addressed class imbalance with SMOTE
- Resolved hyperparameter tuning issues with manual tuning for XGBoost
- Adjusted W&B privacy settings for better collaboration

## Conclusion
This project successfully built a high-performing predictive model for Titanic survival analysis. With strong data preprocessing, feature engineering, and visualization, the model provides meaningful insights and is deployment-ready.
