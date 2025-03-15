# Rain-Prediction-In-Australia-ML-Project
## Project Overview
This project applies machine learning techniques to predict whether it will rain the next day based on historical weather data from the Australian Government's Bureau of Meteorology. The dataset is preprocessed, and multiple classification models are trained and evaluated.

## Dataset
The dataset contains weather-related features, such as:
- **Temperature**: Maximum and minimum daily temperatures  
- **Humidity**: Morning and afternoon humidity levels  
- **Wind Speed**: Various wind speed measurements  
- **Pressure**: Atmospheric pressure readings  
- **Rainfall**: Rainfall amount recorded  
- **RainToday**: Indicator of whether it rained today  
- **RainTomorrow**: Target variable (1 = rain, 0 = no rain)  

## Project Workflow
1. **Data Preprocessing**
   - Handle missing values.
   - Perform feature engineering and selection.
   - Normalize and standardize numerical features.

2. **Model Implementation**
   - Train and compare the following models:
     - Linear Regression
     - K-Nearest Neighbors (KNN)
     - Decision Trees
     - Logistic Regression
     - Support Vector Machine (SVM)

3. **Model Evaluation**
   - Compare models using:
     - Accuracy Score
     - Jaccard Index
     - F1-Score
     - LogLoss
     - Mean Absolute Error
     - Mean Squared Error
     - R2-Score
