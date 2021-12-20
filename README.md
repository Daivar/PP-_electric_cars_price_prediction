# PP4_electric_cars_price_prediction
Electric cars price prediction
The cost of a new EV has dropped significantly over the last decade or so as batteries have become cheaper and as production has scaled up.
And there are already some ultra-low-priced EVs for sale. General Motors sells a tiny 4,500 Eur EV in China, and French automaker Citroën sells a 6,600 Eur city car called the Ami in Europe.
Major carmakers like Tesla and Audi manufacture most types of electric vehicles. The improvement of battery technology in recent years has led to the higher popularity of electric vehicles. Buying an electric vehicle can be a great choice for consumers. The drive quality, low noise levels, and convenience are really great.
image.png

There are, however, many challenges associated with electric vehicles. They have a limited range. Charging the vehicle takes time and can be a hassle sometimes. The availability of charging stations is also a big issue. Incompatibility of charging stations can also be a problem. Despite many challenges and issues, switching to electric vehicles is good for the environment and is more economically viable in the long term. Many have predicted that, by 2040, most of the vehicles will be electric.

There are, however, many challenges associated with electric vehicles. They have a limited range. Charging the vehicle takes time and can be a hassle sometimes. The availability of charging stations is also a big issue. Incompatibility of charging stations can also be a problem. Despite many challenges and issues, switching to electric vehicles is good for the environment and is more economically viable in the long term. Many have predicted that, by 2040, most of the vehicles will be electric.

Data Set on Kaggle: https://www.kaggle.com/kkhandekar/cheapest-electric-cars
The data consists of 180 vehicles and there are some missing values as well. We can conduct various data analytics visualizations to understand the data and information.
Electric Vehicle Data:
- Vehicle Battery capacity (in KWH)
- Acceleration (0-100) in Seconds
- Top Speed in Km/hr
- Range of Vehicle in km
- The efficiency of Vehicle in Wh/km
- Fast charge speed in km/hr
- Drive Configuration
- Number of seats
- Price in Germany (Euro)
- Price in the UK (Pound)

Price and most important parametres Vehicle Battery capacity (KWH), Acceleration, TopSpeed, Range FastChargeSpeed has high corellation. Similarly, vehicle range and KWH has a high correlation of 0.89, it is obvious as the battery capacity, more will be the range of the vehicle.
image.png

Drive column will be encoded - front-wheel drive is saved as 1, rear-wheel drive as 2 and all-wheel drive as 3. Basically, the reason is that data is as text, but is categorical data.

Machine Learning Model For Price Prediction of Electric Vehicles

Acc (Accuracy) using Random Forest Regressor 0.81
Acc using Decision Tree Classifier after increasing max deep 0.9

For better metrics used PCA (dimensionality reduction):
image.png

Acc 0.98

Acc (Accuracy) using Random Forest Regressor 0.81
Acc using Decision Tree Classifier after increasing max deep 0.9

image.png

Electric cars dataset is from:
https://www.analyticsvidhya.com/blog/2021/09/data-analysis-and-price-prediction-of-electric-vehicles/#h2_6

https://www.kaggle.com/prateekmaj21/electric-cars-data-analysis/data

more about Electric Cars prices:
https://www.cnbc.com/2021/10/28/elon-musks-13-year-old-prediction-on-low-cost-electric-cars-came-true.html

https://evadoption.com/ev-sales/ev-sales-forecasts/

https://www.gocompare.com/motoring/electric-cars/electric-car-adoption-prediction/
