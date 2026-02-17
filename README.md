# Waiter Tips Prediction

## Project Description
This project predicts the tip amount for a waiter based on various factors such as total bill, number of guests, gender, smoking status, day, and time.

## Dataset
Columns:

| Column       | Description |
|--------------|-------------|
| total_bill   | Total bill including tax |
| tip          | Tip given in dollars |
| sex          | Gender of the payer |
| smoker       | Whether the person smokes |
| day          | Day of the week |
| time         | Lunch or Dinner |
| size         | Number of people |

## Libraries
- pandas, numpy  
- plotly.express  
- sklearn (train_test_split, LinearRegression)

## Steps
1. Load dataset  
2. Explore data (`head()`, `info()`, `describe()`)  
3. Visualize relationships (`scatter` and `pie`)  
4. One-Hot Encoding categorical features  
5. Split data into X (predictors) and y (target)  
6. Train/test split  
7. Train Linear Regression model  
8. Evaluate model (R² Score, RMSE)  
9. Predict tips for new data  

## Example Prediction
```python
predicted_tip = predict_tip(30, 3, "Male", "No", "Sat", "Dinner")
print(predicted_tip)
