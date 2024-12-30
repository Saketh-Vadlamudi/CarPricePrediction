# Car Price Prediction

## Overview
The **Car Price Prediction** project is a machine learning solution designed to estimate the prices of used cars based on various features like make, model, mileage, year of manufacture, and fuel type. This project leverages **Random Forest Regression** for accurate predictions, enabling users to make informed decisions about car pricing.

---

## Features
- Predicts car prices based on multiple input features.
- Handles categorical and numerical data efficiently.
- Employs feature engineering to improve model performance.
- Provides insights into key factors influencing car prices.

---

## Dataset
The dataset contains the following features:
- **Make**: Manufacturer of the car.
- **Model**: Specific model of the car.
- **Year**: Year of manufacture.
- **Mileage**: Distance traveled by the car.
- **Fuel Type**: Type of fuel used (Petrol/Diesel/Electric/etc.).
- **Price**: Target variable indicating the selling price of the car.

---

## Tools & Technologies
- **Programming Language**: Python
- **Libraries**: 
  - Pandas
  - NumPy
  - scikit-learn
  - Matplotlib
  - Seaborn
- **Machine Learning Algorithm**: Random Forest Regression

---

## Workflow
1. **Data Preprocessing**: 
   - Handle missing values and outliers.
   - Encode categorical variables.
   - Normalize and scale numerical features.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize distributions, correlations, and trends.
   - Identify factors influencing car prices.

3. **Feature Engineering**:
   - Create derived features to capture important relationships.
   - Perform feature selection based on importance.

4. **Model Building**:
   - Implement a Random Forest Regression model.
   - Optimize hyperparameters using Grid Search or Random Search.

5. **Model Evaluation**:
   - Evaluate the model using metrics like RMSE, MAE, and R².

---

## Results
- The model achieved high accuracy in predicting car prices.
- Key insights into price-driving factors were derived from feature importance analysis.

---

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/Saketh-Vadlamudi/CarPricePrediction.git
   ```
2. Install the required libraries:
``` bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebook or Python script:
``` bash
jupyter notebook CarPricePrediction.ipynb
```
