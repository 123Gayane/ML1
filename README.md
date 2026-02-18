# Waiter Tips Prediction — Machine Learning Project

## Introduction

In this project, I used Machine Learning to predict how much tip a customer is likely to leave in a restaurant. The prediction is based on several factors such as the total bill amount, number of people at the table, gender, smoking status, day of the week, and time of the meal.

The main goal of this project is to analyze real-world data and build a prediction model using the Linear Regression algorithm.

---

## How to Get Started

To run this project, follow these steps:

1. Download or clone the project from GitHub
2. Install Python 3 on your computer
3. Install the required libraries:

```
pip install pandas numpy plotly scikit-learn
```

4. Open the project in Jupyter Notebook
5. Make sure the `tips.csv` dataset file is in the same folder as the notebook

---

## How to Run and Test the Project

1. Open the notebook in Jupyter Notebook
2. Run the cells step by step
3. The program will:

* Load and display the dataset
* Visualize the data with charts
* Encode categorical text data into numbers
* Train a Linear Regression model
* Evaluate model accuracy
* Make an example prediction

All outputs and visualizations will appear directly in the notebook.

---

## Libraries and Functions Used

### Pandas

Used for data handling and preprocessing:

* `read_csv()` — loads the dataset
* `get_dummies()` — converts categorical data into numeric format
* `corr()` — calculates correlation between features

### Plotly Express

Used for data visualization:

* `scatter()` — shows relationships between features
* `pie()` — displays category distribution
* `histogram()` — shows value distribution

### Scikit-learn

Used to build and evaluate the machine learning model:

* `train_test_split()` — splits data into training and testing sets
* `LinearRegression` — prediction algorithm
* `model.fit()` — trains the model
* `model.score()` — measures accuracy (R² score)
* `model.predict()` — makes predictions

---

## Output Examples

During execution, the notebook produces:

* Scatter plot showing the relationship between total bill and tip
* Pie chart of customer gender distribution
* Histogram of tip values
* Correlation table between all features
* Printed model accuracy (R² score)
* Example predicted tip for a new customer

---

## Model Results

The project uses the Linear Regression algorithm to predict tip amounts.

* Model accuracy is measured using the **R² score**
* The trained model is able to estimate tips based on customer and bill information
* An example prediction is generated to demonstrate real-world usage

This shows that machine learning can successfully model relationships between restaurant data and tipping behavior.
