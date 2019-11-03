# new_york_taxi_fare_prediction
# Shark Attack Analysis
Analyzing the shark attack dataset with respect to Day, Month and Year of attack outside the US.

## Install
This project is built using Python and the following Python libraries:
- Numpy
- Pandas
- Seaborn
- Matplotlib

As this is a ipynb file, you will need a software to run the [Jupyter Notebook](https://github.com/sriganeshlokesh/human_activity_recognition_lstm_keras/blob/master/HAR_LSTM.ipynb)

If Python is not installed on your computer, it is highly recommended to install [Anaconda Distribution](https://www.anaconda.com/distribution/)
The Anaconda Distribution contains all the above packages and more installed.

## Code

The notebook file for this project is `shark_attack_final.ipynb`. 

This notebook shows the pattern of shark attacks based on the day, month and year in the regions outside the US.

## Run

In a terminal or command window, run the following commands:
```python
jupyter notebook shark_attack_final.ipynb
```
or

```python
ipython notebook shark_attack_final.ipynb
```
This will open the Jupyter Notebook software and project file in your web browser.

## Data

Dataset used in this project is `GSAF5-1.xls` from the [Global Shark Attack File](https://www.sharkattackfile.net/).


#### Features:

`Case-Number`: Unique number given to the case filed.

`Date`: Date in the format 'dd-mmm-yyyy'.

`Year`: the year in which the accident took place.

`Type`: the nature of attack - ('Provoked' 'Unprovoked' 'Unconfirmed' 'Unverified' 'Questionable'
 'Watercraft' 'Invalid' 'Under investigation' 'Sea Disaster').

`Country`: country where the attack took place.

`Area`: State where the attack took place.

`Location`: Name of the beach.

`Activity`: activity being performed during the time of attack.

`Name`: name of victim.

`Sex`: gender of victim.

`Age`: age of victim.

`Injury`: after effects of attack.

`Fatal(Y/N)`: the nature of injury.

`Time`: time of attack.

`Species`: species of shark.

`Investigator or Source`: name and company of the investigator.

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

