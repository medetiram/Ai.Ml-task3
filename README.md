AI & ML Internship – Task 3: Linear Regression
Objective
Implement and understand simple & multiple linear regression using the Housing Price Prediction Dataset.
Dataset
Dataset Name: Housing Price Prediction Dataset
File Used: Housing.csv
Tools & Libraries
Python
Pandas
Scikit-learn
Matplotlib
Seaborn

Steps Followed
1. Import & Preprocess Data
Loaded dataset using pandas
Handled categorical variables using pd.get_dummies()

2. Train-Test Split
Used train_test_split from sklearn.model_selection
80% training, 20% testing

3. Model Training
Trained a LinearRegression model from sklearn.linear_model

4. Model Evaluation
Mean Absolute Error (MAE): ~ ₹970,000
Mean Squared Error (MSE): ~ ₹1.75 Trillion
R² Score: 0.65 (65% variance explained)

5. Plotting
Plotted regression line for the area feature vs. price

6. Coefficient Interpretation
Printed all coefficients to understand feature impact

Sample Output
Metric	Value
MAE	₹970,043
MSE	₹1.75 Trillion
R²	0.653

