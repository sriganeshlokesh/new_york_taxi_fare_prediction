# New York Taxi Fare Prediction
Predicting the taxi fare amount in the city of New York and discovering some patterns based off of Latitude and Longitude boundaries. Providing insight on taxi usage and distribution of fare amount in the 5 boroughs of New York - Manhattan, Queens, Brooklyn, Bronx and Staten Island.

## Install
This project is built using Python and the following Python libraries:
- Numpy
- Pandas
- Seaborn
- Matplotlib
- folium maps

As this is a ipynb file, you will need a software to run the [Jupyter Notebook](https://github.com/sriganeshlokesh/new_york_taxi_fare_prediction/blob/master/New_York_Taxi.ipynb)

If Python is not installed on your computer, it is highly recommended to install [Anaconda Distribution](https://www.anaconda.com/distribution/)
The Anaconda Distribution contains all the above packages and more installed.

## Code

The notebook file for this project is `New_York_Fare.ipynb`. 

This notebook deals with the Exploratory Data Analysis and Machine Learning implementation of the New York City Taxi Fare Prediction dataset from Kaggle.

## Run

In a terminal or command window, run the following commands:
```python
jupyter notebook New_York_Fare.ipynb
```
or

```python
ipython notebook New_York_Fare.ipynb
```
This will open the Jupyter Notebook software and project file in your web browser.

## Data

Dataset used in this project is `train.csv` from the [New York Taxi Fare Prediction](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction).


#### Features:

##### ID

`key` - Unique string identifying each row. Comprised of pickup_datetime plus a unique integer.

##### Features

`pickup_datetime` - timestamp value indicating when the taxi ride started.

`pickup_longitude` - float for longitude coordinate of where the taxi ride started.

`pickup_latitude` - float for latitude coordinate of where the taxi ride started.

`dropoff_longitude` - float for longitude coordinate of where the taxi ride ended.

`dropoff_latitude` - float for latitude coordinate of where the taxi ride ended.

`passenger_count` - integer indicating the number of passengers in the taxi ride.

##### Target

`fare_amount` - float dollar amount of the cost of the taxi ride.

## Visualizations

#### Heatmap

![Heatmap](https://github.com/sriganeshlokesh/new_york_taxi_fare_prediction/blob/master/img/Heatmap.png)

The heatmap depicts the features which are highly correlated. From the above heatmap we can observe that pickup_latitude, pickup_longitude, dropoff_latitude, dropoff_longitude are highly correlated.

#### Pickup Distribution

![Pickup](https://github.com/sriganeshlokesh/new_york_taxi_fare_prediction/blob/master/img/Pickup.png)

Pickup distribution gives us an idea of the highly used pickup service location. From the coordinates, we see that Manhattan has the highest number of pickups.

#### Dropoff Distribution 

![Dropoff](https://github.com/sriganeshlokesh/new_york_taxi_fare_prediction/blob/master/img/Dropoff.png)

Dropoff distribution gives us an idea of the frequent dropoff location. From the coordinates, we see that Manhattan has the highest number of dropoffs.

#### Fare Amount Distribution for JFK Airport

![Fare JFK](https://github.com/sriganeshlokesh/new_york_taxi_fare_prediction/blob/master/img/Distribution%20of%20Fare%20Amount.png)

The plot describes the fare amount to and from the airport as compared to other pickup and drop off locations. We can infer that the using the taxi service from the airport will cost more as compared to other pickup locations.

#### Borough Pickup Distribution

![Borough Pickup](https://github.com/sriganeshlokesh/new_york_taxi_fare_prediction/blob/master/img/Pickup%20Distribution.png)

Manhattan has the highest pickup density as compared to the other 4 boroughs. This is followed by Queens.

#### Borough Dropoff Distribution

![Borough Dropoff](https://github.com/sriganeshlokesh/new_york_taxi_fare_prediction/blob/master/img/Dropoff%20Distribution.png)

This plot is similar to the pickup distribution.Manhattan has the highest dropoff density as compared to the other 4 boroughs. This is followed by Queens.

#### Borough Fare Distribution

![Borough Fare](https://github.com/sriganeshlokesh/new_york_taxi_fare_prediction/blob/master/img/Borough%20Distribution.png)

Here, we picturize the fare amount for the 5 boroughs. No suprise here, Manhattan has a high fare amount as compared to the other boroughs followed by Queens.


