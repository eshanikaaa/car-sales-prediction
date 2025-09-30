# car-sales-prediction
This project predicts the price of used cars based on features such as manufacturer, engine size, fuel type, year of manufacture, and mileage. The model uses a Random Forest Regressor to achieve high prediction accuracy.
The dataset contains 49,988 entries with numeric and categorical features. Categorical features are converted to numeric values using Label Encoding.
**Data Preprocessing**
Label Encoding applied to categorical features (Manufacturer, Fuel type).
Missing values handled (if any).
All features converted to numeric for model training.

**Model**
Algorithm: Random Forest Regressor
**Hyperparameters:**
n_estimators=100
random_state=42
Train-test split: 80% training, 20% testing

**Evaluation Metrics**
Metric	Value	Description
Mean Squared Error (MSE)	example: 1,234,567	Average squared difference between predicted and actual prices
Mean Absolute Error (MAE)	example: 890	Average absolute difference between predicted and actual prices
R² Score	0.980	98% of variance in prices explained by the model

**Results**
The model shows excellent performance with an R² score of 0.98, meaning it can predict car prices with high accuracy.
Feature importance analysis shows which features most influence car prices.

**Libraries Used**
pandas
numpy
scikit-learn
matplotlib
