# Project Title

Diamond price prediction and deployment using AWS

## Project Overview
The primary goal of this project is to build robust machine learning models capable of predicting the price of diamonds based on various attributes, such as carat weight, cut, color, clarity, and more. Predicting diamond prices with precision is essential for both buyers and sellers in the diamond industry.

AWS Deployment: In addition to developing the predictive models, this project places a strong emphasis on deploying these models using AWS services. The AWS cloud platform provides an ideal environment for hosting machine learning models, ensuring scalability, reliability, and cost-efficiency.
## Install
* NumPy
* Pandas
* Matplolib
* Seaborn
* Sklearn
Python (version 3.8): This project is primarily built in Python, and you'll need it to run the code.
## Data
https://www.kaggle.com/code/karnikakapoor/diamond-price-prediction/input

The datasets contain following features:
* Carat: The weight of the diamond, typically measured in carats.
* Cut: The quality of the cut, which can be categories like 'Fair', 'Good', 'Very Good', 'Premium', or 'Ideal'.
* Color: The diamond color, usually represented on a scale from 'D' (colorless) to 'Z' (light yellow).
* Clarity: A measurement of how clear the diamond is, with categories like 'IF' (internally flawless), 'VVS1', 'VVS2', 'VS1', 'VS2', 'SI1', 'SI2', 'I1', 'I2', 'I3'.
* Depth: The height of the diamond, measured from the culet to the table, divided by its average girdle diameter.
* Table: The width of the diamond's table (the flat top facet) expressed as a percentage of its average diameter.
* Price: The price of the diamond in USD, which is the target variable for prediction.
* X, Y, Z: The length, width, and depth of the diamond, respectively, in numerical values.
Dependent variable price based on the above parameters.
## Model Development
* Data Cleaning: Handle missing values, outliers, and inconsistencies in the dataset.
* Feature Engineering: Create new features or transform existing ones to improve model performance.
* Encoding Categorical Variables: Convert categorical variables like 'cut', 'color', and 'clarity' into numerical representations using techniques like one-hot encoding.
* Split your dataset into training and testing sets. A common split is 80% for training and 25% for testing. You can use libraries like Scikit-Learn to perform this split.
Models used:

1. Linear Regression

2. Lasso

3. Ridge

4. ElasticNet

* R-squared (R²): A measure of how well the model explains the variance in the target variable. A higher R² indicates a better fit.

* Training shows ElasticNet shows more R2 value than other models about 0.93


## Deployment
For deploying a Docker container, you can use Amazon app runner.



```
