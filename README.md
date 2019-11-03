# New York Taxi Fare Prediction
Predicting the taxi fare amount in the city of New York and discovering some patterns based off of Latitude and Longitude boundaries. Providing insight on taxi usage and distribution of fare amount in the 5 boroughs of New York - Manhattan, Queens, Brooklyn, Bronx and Staten Island.

## Install
This project is built using Python and the following Python libraries:
- Numpy
- Pandas
- Seaborn
- Matplotlib
- folium maps

As this is a ipynb file, you will need a software to run the [Jupyter Notebook](https://github.com/sriganeshlokesh/human_activity_recognition_lstm_keras/blob/master/HAR_LSTM.ipynb)

If Python is not installed on your computer, it is highly recommended to install [Anaconda Distribution](https://www.anaconda.com/distribution/)
The Anaconda Distribution contains all the above packages and more installed.

## Code

The notebook file for this project is `new_york_taxi_fare.ipynb`. 

This notebook deals with the Exploratory Data Analysis and Machine Learning implementation of the New York City Taxi Fare Prediction dataset from Kaggle.

## Run

In a terminal or command window, run the following commands:
```python
jupyter notebook new_york_taxi_fare.ipynb
```
or

```python
ipython notebook new_york_taxi_fare.ipynb
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

#### Day of Week

![Day of week](https://github.com/sriganeshlokesh/shark_attack_analysis/blob/master/images/day_img.png)

Here we can observe that Saturday has the highest number of shark attacks. Since Saturday is a weekend, people tend to encounter shark attacks.

#### Continent

![Continent](https://github.com/sriganeshlokesh/shark_attack_analysis/blob/master/images/continent_img.png)

From the plot, we can see that Australia has the highest number of shark attacks.

#### Month 

![Month](https://github.com/sriganeshlokesh/shark_attack_analysis/blob/master/images/month_img.png)

January has the highest number of shark attacks. The reason behind this is, In Australia, the month of january is considered to be Summer.

#### Year

![Year](https://github.com/sriganeshlokesh/shark_attack_analysis/blob/master/images/year_img.png)

As seen from the plot, 2011 has the highest number of shark attacks.

