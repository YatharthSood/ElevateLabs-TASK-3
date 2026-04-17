# ElevateLabs-TASK-3
HOUSING PRICING PREDICTION

This project uses a housing dataset to predict property prices with Linear Regression. It demonstrates data preprocessing, model training, evaluation, and visualization.

Steps
Import Libraries: pandas, numpy, matplotlib, scikit-learn.
Load Dataset: Read Housing.csv into a DataFrame.

Preprocess Data:
Convert categorical variables (yes/no, furnishingstatus) into dummy/indicator variables.
Separate features (X) and target (y).
Train-Test Split: Divide data into training (80%) and testing (20%).
Model Training: Fit a Linear Regression model using training data.
Prediction: Predict housing prices on test data.
Evaluation: Calculate MAE, MSE, and R² score.
Interpret Coefficients: Identify which features most influence price.
Visualization: Plot actual vs predicted prices.

Results

MAE: Average error between predicted and actual prices.

MSE: Penalizes larger errors.

R²: Explains variance captured by the model.
