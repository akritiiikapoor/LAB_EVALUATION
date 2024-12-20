# LAB_EVALUATION

# Fuel Efficiency Prediction Using Regression Models


## Project Overview
This project involves predicting fuel efficiency using various regression models. The goal was to preprocess the data, train different machine learning models, and select the best-performing model based on the R² score.

### What I Did:
- Selected the **Target5** variable based on the roll number --102203679.
- Preprocessed the dataset with techniques like outlier removal, normalization, and transformation.
- Split the dataset into **70% training** and **30% testing**.
- Trained multiple regression models and selected the best model based on R² performance.
- Analyzed the model's performance with visualizations (error plots, learning curves, feature importance).


### Features and Target:
- **Features**: Various columns representing engine performance, fuel consumption, and vehicle characteristics.
- **Target Variable**: Fuel Efficiency (Target5).


### Step 1: Data Preparation
- Loaded the **Fuel Performance Dataset**.
- Selected the appropriate target (`Target5`) and dropped all other targets.

### Step 2: Splitting the Data
- Divided the dataset into **70% training** and **30% testing**.

### Step 3: Data Preprocessing
Applied preprocessing steps to improve model performance.

### Step 4: Model Training and Comparison
- Trained and compared multiple regression models using PyCaret:
   - Random Forest Regressor (`rf`)
   - AdaBoost Regressor (`ada`)
   - Extra Trees Regressor (`et`)
   - Gradient Boosting Regressor (`gbr`)
   - Linear Regression (`lr`)
   - And many more...

- Stored the R² scores for all models and selected the **best-performing model**.

### Step 5: Model Analysis and Visualization
- Generated numerous plots for the best model:
   - **Error Plot**: To analyze prediction errors.
   - **Learning Curve**: To study the model's learning behavior.
   - **Feature Importance Plot**: To identify the most influential features.


## Results

- **Best Model**: Light Gradient Boosting Machine (`lightgbm`)  
- **R² Score**: 0.8291


  before data preprocessing and applying models:
 - r^2 value was: 0.7692(lightgbm--bestmodel)
  ![Screenshot 2024-12-21 014304](https://github.com/user-attachments/assets/dc307b5d-a7fa-40c6-9cb5-d8586bc9ad88)

after data-preprocessing and applying various models :
-r^2 value became: 0.8291 (lightgbm -best model)
![Screenshot 2024-12-21 014209](https://github.com/user-attachments/assets/8da7de1e-4faa-4de9-bd79-9b0902d17b5c)
