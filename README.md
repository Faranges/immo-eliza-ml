# Immo Eliza - Machine Learning: Property Price Prediction 

A machine learning project that builds and compares three different regression models to predict real estate prices in Belgium.

## 📋 Project Overview
This project was developed for Immo Eliza to create a machine learning model for predicting property prices in Belgium. The solution implements and compares three different regression algorithms to find the most accurate price predictions.

## 🎯 Project Objectives
* Preprocess data for machine learning
* Apply regression in a real-life context
* Explore multiple machine learning models for regression
* Evaluate model performance using appropriate metrics
* Implement hyperparameter tuning and cross-validation to further improve models

## 🛠️ Technical Implementation
### Models Implemented
1) Linear Regression - Baseline model
2) Random Forest - Ensemble method for non-linear relationships
3) XGBoost - Advanced gradient boosting for improved performance

### Data Pipeline
* Data Cleaning: Handling duplicates, missing values, and irrelevant columns
* Preprocessing: Imputation, one-hot encoding, and feature scaling
* Feature Selection: Correlation analysis and multicollinearity handling
* Model Training: Three different algorithms with proper train-test split
* Evaluation: Comprehensive metrics and overfitting analysis

## 📊 Performance Metrics
Models were evaluated using:

* R-squared (R²)
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)
* Cross-validation scores

## 🚀 Installation & Usage
## Prerequisites
* Python 3.8+
* Virtual environment recommended
  
## Setup
```
# Clone the repository
git clone https://github.com/yourusername/immo-eliza-ml.git

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  

# Install dependencies
pip install -r requirements.txt

```
## Running the Project
````
# Train models
python train.py

# Make predictions
python predict.py
````

## 📈 Results Summary
The project implemented three prediction models with the following key findings:

* XGBoost demonstrated the best overall performance
* Proper preprocessing significantly improved model accuracy
* Feature selection helped reduce overfitting


## 🔮 Future Improvements
* Hyperparameter optimization with GridSearchCV
* Explore more regularization techniques
* Feature engineering for additional predictive power
  
* Integration in pipeline. 
                          
<br>               

*Project completed as part of machine learning consolidation during the BeCode Data Science & AI course - Duration: 4 days*