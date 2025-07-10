# Tamizhan-Skills_Intenrship_Projects
Projects which are gonna help in real life

# Project 1: Sales Forecasting with Linear Regression

Hi, this is my Sales Forecasting project. The goal was to predict future sales. I started by loading a supermarket dataset into a Pandas DataFrame. Then, I processed the data by converting the date column and calculating the total sales for each day. The key step was creating a 'Days' feature for my model to use.
I then trained a Linear Regression model using Scikit-learn. Here is the final result: this graph shows the actual sales as blue dots and my model's prediction as the red line.
As you can see, the model drew a straight line, but the actual sales are all over the place. My conclusion is that linear regression is too simple for this data, and we'd need a more advanced model for better accuracy. Thank you.
This is just a brief explanation of the project

📝 About the Project

This project aims to forecast daily supermarket sales using a Linear Regression model. The goal is to analyze historical sales data to predict future revenue trends. The model is built in Python using libraries such as Pandas for data manipulation, Scikit-learn for machine learning, and Matplotlib for visualization.

---

⚙️ How to Use

To run this project yourself, follow these steps:

1.  Clone or download this repository.
2.  Upload the Jupyter Notebook (`.ipynb` file) to Google Colab or a local Jupyter environment.
3.  Upload the dataset (`SuperMarket Analysis.csv`).
4.  Run the cells in the notebook from top to bottom.

---

📊 Results and Conclusion

The model was trained on daily aggregated sales data. The primary feature used for prediction was the number of days elapsed since the start of the data period.

The final output is a visualization comparing the actual daily sales to the predictions made by the linear model.

Analysis:

* Actual Sales (Blue Dots): The plot shows that actual daily sales have high variance, meaning they fluctuate significantly from day to day.
* Predicted Trend (Red Line): The linear regression model generated a straight line with a slight negative slope. This indicates that the model found a very subtle overall decreasing trend in the sales data.

Conclusion:

A simple Linear Regression model is not sufficient for accurately forecasting daily sales for this dataset. The model fails to capture the high daily volatility. While it identified a minor downward trend, its predictive power is low because the actual data does not follow a linear pattern. For a more accurate forecast, a more complex model (like ARIMA or seasonal decomposition) would be necessary.
