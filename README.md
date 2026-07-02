# House Price Prediction using Linear Regression

## Project Overview

This project demonstrates how to use Linear Regression to predict house prices using a housing dataset. Both Simple Linear Regression and Multiple Linear Regression are implemented to understand how different features affect the price of a house. The models are trained, evaluated, and visualized using Python and Scikit-learn.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Dataset

The project uses the Housing dataset, which contains information about different house features such as area, number of bedrooms, bathrooms, parking, furnishing status, and the corresponding house price.

---

## Steps Performed

- Imported the required Python libraries.
- Loaded and explored the dataset.
- Checked the dataset information and summary statistics.
- Checked for missing values.
- Converted categorical columns into numerical values using Label Encoding and One-Hot Encoding.
- Split the dataset into training and testing sets.
- Built a Simple Linear Regression model using the house area.
- Built a Multiple Linear Regression model using all available features.
- Predicted house prices using both models.
- Evaluated the models using MAE, MSE, and R² Score.
- Visualized the results using graphs.
- Displayed and interpreted the regression coefficients.

---

## Observations

### Dataset
- The dataset contains information about different house features and their prices.
- No missing values were found in the dataset.
- Categorical features were successfully converted into numerical values before training the model.

### Simple Linear Regression
- The regression line shows a positive relationship between house area and price.
- As the area of a house increases, its predicted price also increases.
- Most data points are close to the regression line, indicating a reasonable linear relationship between area and price.

### Multiple Linear Regression
- The Actual vs Predicted graph shows that most predicted prices are close to the actual prices.
- Some expensive houses have larger prediction errors than others.
- Overall, the model performs reasonably well in predicting house prices.
- Using multiple features improves the prediction compared to using only a single feature.

### Model Evaluation
- MAE was used to measure the average prediction error.
- MSE was used to measure the squared prediction error.
- R² Score was used to measure how well the model explains the variation in house prices.

---

## Project Structure

```
Task_three_linear_regression/
│
├── Task_three.ipynb
├── Housing.csv
├── README.md
└── images/
    ├── simple_linear_regression.png
    └── multiple_linear_regression.png
```

---

## Conclusion

This project helped me understand how Linear Regression works for predicting continuous values. I learned how to preprocess a dataset, build both Simple and Multiple Linear Regression models, evaluate their performance, and interpret the results using different evaluation metrics and visualizations.