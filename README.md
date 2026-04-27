# Laptop_Price_Prediction
# Laptop Price Prediction using Machine Learning

##  Overview
This project focuses on predicting laptop prices based on their specifications using machine learning techniques. It analyzes features such as RAM, storage, processor, graphics, and other attributes to estimate the price of a laptop accurately.

---

##  Objective
The main objective of this project is to:
- Predict laptop prices using regression models
- Understand the impact of different features on price
- Compare multiple machine learning models
- Identify the best-performing model

---

##  Dataset
The dataset contains information about laptops, including:
- Brand
- Processor details
- RAM
- SSD / HDD storage
- Graphics card
- Operating system
- Rating
- Price (target variable)

---

##  Technologies Used
- Python 
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost
- SHAP (for model interpretability)

---

## Project Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Converting string values to numeric
   - Cleaning inconsistent data

2. **Feature Engineering**
   - Created new features like:
     - Total Storage
     - Performance Score
     - Price per GB

3. **Exploratory Data Analysis (EDA)**
   - Scatter plots
   - Box plots
   - Heatmaps
   - Distribution analysis

4. **Model Training**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - K-Nearest Neighbors (KNN)
   - XGBoost Regressor

5. **Model Evaluation**
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
   - R² Score

6. **Model Comparison**
   - Compared performance of all models
   - Selected best model based on R² score

7. **Model Interpretation**
   - Feature importance analysis
   - SHAP values visualization

---

##  Results
- Ensemble models like **Random Forest** and **XGBoost** performed better compared to other models.
- Important features influencing price:
  - Price per GB
  - SSD
  - Total Storage
  - Processor
  - Performance Score

---

## Author - Janya J Jetty
