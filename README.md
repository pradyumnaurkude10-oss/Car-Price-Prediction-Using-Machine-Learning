# Car-Price-Prediction-Using-Machine-Learning
Overview
This project predicts the selling price of used cars using Machine Learning algorithms. The model is trained on historical car data and uses important vehicle features to estimate car prices.
Two regression models are implemented in this project:
Linear Regression
Lasso Regression
The project is developed in Python using Jupyter Notebook.


Dataset Information
The dataset contains various features related to cars:

Feature	Description
Car_Name	Name of the car
Year	Manufacturing year
Selling_Price	Selling price of the car
Present_Price	Current ex-showroom price
Driven_kms	Total kilometers driven
Fuel_Type	Type of fuel used
Seller_Type	Dealer or Individual
Transmission	Manual or Automatic
Owner	Number of previous owners


Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook


Machine Learning Models
1. Linear Regression : It is used to establish the relationship between independent variables and the target variable (selling price).
2. Lasso Regression : It helps in feature selection and reduces overfitting by applying regularization.


Project Workflow
Importing Dependencies
Loading Dataset
Data Preprocessing
Encoding Categorical Features
Splitting Data into Training and Testing Sets
Training Machine Learning Models
Evaluating Models using R² Score
Visualizing Predictions
Predicting Car Prices


Model Evaluation
The models are evaluated using:
R² Score
Scatter Plot Visualization


Output Visualization
The notebook includes visualizations comparing:
Actual Prices vs Predicted Prices
Training Data Performance
Test Data Performance

The project compares the performance of Linear Regression and Lasso Regression models.


Future Improvements can be are as follows:
Add more advanced regression models
Build a web application using Flask or Streamlit
Deploy the model online
Improve prediction accuracy using feature engineering
