# Used car value prediction

Introduction:
The goal of this analysis was to predict the price of used cars based on various features available in the dataset. The dataset contains features such as year, mileage, and other relevant characteristics of the cars. Our primary focus was to evaluate how different factors impact the price of used cars and assess the performance of linear and ridge regression models in predicting car prices.

**Data Preparation and Preprocessing**:

**Data Exploration**:
* Check duplicate records and delete them
* Some of the vehicle data are with Price=0 and Odometer=0, discard these records
* There are lot of models and manufacturers. Consider top 10 models and manufacturer data
* Calculate the log value of the price and the odometer and remove the outliers in IQR[Inter Quartile Range]

**Conclusion:**

Based on the used car analysis and the different model evaluations, the findings are:
* Year - More recent cars have a higher value compared tothe older once
* Odometer: It has negative correlation with price. More than odometer value, lesser the price
* Type of the car: Sedan cars are most popular cars
* Drive mode: FWD and the 4WD are the most popular drive mode cars
* Manufacturer: Jeep and Chevrolet has more demand
