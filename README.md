# Seol-Bike-Sharing-Demand-Prediction
![image](https://github.com/Pradeep1023/Seol-Bike-Sharing-Demand-Prediction/assets/112772717/1642379b-d5aa-46f8-b875-d0309b04af49)

![image](https://github.com/Pradeep1023/Seol-Bike-Sharing-Demand-Prediction/assets/112772717/3f824899-b63d-4e31-87f2-a47f387eea38)


**Table of Content**

Introduction

Problem Statement

Data Description

Steps Involved

Algorithms Used

Conclusion

![image](https://github.com/Pradeep1023/Seol-Bike-Sharing-Demand-Prediction/assets/112772717/c973c5e2-849e-4a41-9ce0-fc79affa4683)


**Introduction**

Bike-sharing systems have gained worldwide popularity as an environmentally sustainable, convenient, and cost-effective transportation strategy. These systems provide short-term access to bicycles for a fee or even for free, promoting cleaner air and reducing emissions. By strategically placing docking stations throughout cities, bike-sharing systems offer convenient access to bikes for short trips and seamless integration with other modes of transport. They offer convenience by placing docking stations throughout cities, allowing users to easily access bikes for shorter trips and integrate with other modes of transport. Economically, they provide a cheaper alternative to owning a vehicle, benefiting occasional riders and tourists.

![image](https://github.com/Pradeep1023/Seol-Bike-Sharing-Demand-Prediction/assets/112772717/794645e4-917b-4e1f-9795-afba5b6c8004)


**Problem Statement**

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

![image](https://github.com/Pradeep1023/Seol-Bike-Sharing-Demand-Prediction/assets/112772717/a8350716-f1b4-47dc-aa96-3e025adbdaac)


**Data Description**
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
Attribute Information:
* Date : year-month-day
* Rented Bike count - Count of bikes rented at each hour
* Hour - Hour of he day
* Temperature-Temperature in Celsius
* Humidity - %
* Windspeed - m/s
* Visibility - 10m
* Dew point temperature - Celsius
* Solar radiation - MJ/m2
* Rainfall - mm
* Snowfall - cm
* Seasons - Winter, Spring, Summer, Autumn
* Holiday - Holiday/No holiday
* Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

![image](https://github.com/Pradeep1023/Seol-Bike-Sharing-Demand-Prediction/assets/112772717/1b4ad787-c8b0-4fbb-9720-1e85ec1bf377)


**Steps Involved** 

Data Preprocessing : Checked for outliers, null values, duplicated values and changed data type.

Feature Extraction : Created new columns such as Day, Month, and Year from Date column .

Exploratory Data Analysis : Performed Univariate, Bivariate, and Multivariate analysis with various graphs and plots to better understand the distribution of features and their relationships.

Feature Selection : Plotted heatmap to check the correlation between features and dropped Dew point Temperature which was highly correlated with other independent feature.

One hot encoding : Created dummies for the categorical features present in the dataset Seasons, Holiday, Weekend, and Functioning Day.

Implemented different regression algorithms

Hyperparameter tuning 

![image](https://github.com/Pradeep1023/Seol-Bike-Sharing-Demand-Prediction/assets/112772717/942053f1-0a33-4733-8814-dfcf0876cb42)


**Algorithms Used**

Linear Regresson.

Polynomial Regresson.

Ridge Regression.

Lasso Regression.

Decision Tree.

Decision Tree with cross-validation

Random Forest

![image](https://github.com/Pradeep1023/Seol-Bike-Sharing-Demand-Prediction/assets/112772717/9b0c5d7c-5ba7-4590-981a-028e4157cbd3)


**Conclusion**

* Temprature and Humidity have a strong correlation with dependent feature i.e. rented bike counts.
  
* Temperature and Dew point temprature are highly correlated.

* Demand of the bikes decreases during holidays and weekends.

* During office starting and ending hours demnad is highest as compare to other hours.

* On weekends demand is higher in working hours as compare to non holiday.

* In the month of December, January, and February demand of the bikes are lower, while in month of June and July demand is highest.

* Random Forest is best fit for this dataset because it's giving r2 score of 93% on training set and r2 score of 90% on the testing set. 

![image](https://github.com/Pradeep1023/Seol-Bike-Sharing-Demand-Prediction/assets/112772717/f2a3dc99-180d-4b6a-ab0f-e3cbae715c5a)
