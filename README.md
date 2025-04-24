# 🌧️ Rain Prediction in Australia - Machine Learning Project

## 📌 Project Overview
This project applies machine learning techniques to predict whether it will rain tomorrow, using historical weather data from the Australian Government’s Bureau of Meteorology. It is a binary classification task with multiple models implemented and evaluated.

## 📊 Dataset Features
The dataset contains weather-related features including:
- **Temperature**: Maximum and minimum daily temperatures
- **Humidity**: Morning and afternoon humidity levels
- **Wind Speed**: Recorded at different times of the day
- **Pressure**: Atmospheric pressure values
- **Rainfall**: Daily rainfall in mm
- **RainToday**: Whether it rained today (Yes/No)
- **RainTomorrow** *(Target)*: Whether it will rain tomorrow (Yes/No)

## 🔄 Project Workflow

### 1. Data Preprocessing
- Handled missing values using imputation techniques.
- Performed feature engineering and selection.
- Normalized and standardized numerical features for model compatibility.

### 2. Model Implementation
Trained and compared the performance of several classification models:
- **Linear Regression**
- **K-Nearest Neighbors (KNN)**
- **Decision Trees**
- **Logistic Regression**
- **Support Vector Machine (SVM)**

### 3. Model Evaluation
Model performance was assessed using the following metrics:
- **Accuracy Score**
- **Jaccard Index**
- **F1-Score**
- **LogLoss**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**
