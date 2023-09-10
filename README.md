# Bike-Sharing-Demand-Prediction
## **Problem Statement**

🎯 Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## 📖 **DataSet Description**
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Attribute Information:

Date: year-month-day

Rented_Bike_Count - Count of bikes rented at each hour

Hour - Hour of the day

Temperature-Temperature in Celsius

Humidity - %

Windspeed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

## 🛠  **Tools and Technologies used**

The programming language used in this project is Python. The following libraries were used for data analysis and data visualization and to build a classifier to predict the price range of mobile phones.

* Pandas: For loading the dataset and performing data wrangling

* Matplotlib: For data visualization.

* Seaborn: For data visualization.

* NumPy: For some math operations in predictions.

* Sklearn: For model fitting and prediction.

## 📑 **Steps involved**

* Data Preprocessing: Checked for outliers, incorrect values, missing values, duplicates and performed data type correction.

* Feature Extraction: Created new columns such as Day, Month, Year, and Weekend from Date column.

* Exploratory Data Analysis: Performed Univariate, Bivariate, and Multivariate analysis with various graphs and plots to better understand the distribution of features and their relationships.

* Feature Selection: Checked the VIF value (measure of multicollinearity) and dropped Dew point Temperature and Year which were highly correlated with other independent features.

* Feature encoding: The categorical features present in the dataset Seasons, Holiday, Weekend, Functioning Day were dummified.

* Feature Scaling: Brought features to a similar range using MinmaxScaler.

* Implementation of Regression models with Hyperparameter tuning
  
* Model Explainability - LIME

* Evaluation of models using Mean Absolute error, Mean Squared error, Root Mean Squared error, R square, and Adjusted R square.

* Conclusion

## **💻 Algorithms used**

* Linear Regression
  - Multiple Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Elastic net regression
* Tree Based Models
  - Decision Tree Regressor
  - Random Forest Regressor
  - Extreme Gradient Boost
