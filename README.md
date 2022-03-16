# EnerjiSA Energy Data Marathon | TRAI x Coderspace

<p align="center">
	<img src="  " />

</p>

## Table of contents
* [General info](#general-info)
* [Dataset info](#dataset-info)
* [Project info](#project-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Developments](#developments)

## General info
It is Kaggle competition which is held by EnerjiSA Energy company. Our aim was to forecast of solar power plants' production. 
You can reach the competition page via:
https://www.kaggle.com/c/enerjisa-enerji-veri-maratonu

## Project info
Our aim was to forecast of solar power plants' production. We have given data from 01.01.2019-30.11.2021 and we need forecast the production for 01.12.2021 – 31.12.2021. We used time series approach to data and used LGBM for forecasting. Optuna and GridSearchCV is used for optimization.


## Dataset info
Dataset is provided from Enerjisa, these are real datas from past.
Link: https://www.kaggle.com/c/enerjisa-enerji-veri-maratonu/data
You can download it from the link

In the shared data set, the total hourly generation amounts of unlicensed solar power plants located in the Capital region between 01.01.2019 and 30.11.2021 are given. Within this region, there are a total of 848 power plants located in the provinces of Ankara, Çankırı, Kırıkkale, Bartın, Karabük, Kastamonu and Zonguldak. In addition to the total production; Since the production weight is in Ankara, the temperature variables of Ankara province were shared between 01.01.2019 - 31.12.2021. The temperature variables include forecast data for the period 01.01.2019 to 30.11.2021, from 01.12.2021 to 31.12.2021.



We have two tables which are, "generation" and "temperature"

For generation table;

**DateTime:** specifies the time range in which the production was made in date-time format.
**Generation:** Specifies the total production in MWh in the relevant hour range.

For temperature table;

**DateTime:** Specifies the time interval in which temperature variables are observed.
**AirTemperature:** Specifies the air temperature in the hour range in Celsius.
**ComfortTemperature:** Indicates the sensed air temperature in the hour range in Celsius.
**RelativeHumidity:** Specifies the humidity in the hour range.
**WindSpeed:** Specifies the wind speed in the hour range in km/h.
**WindDirection:** Specifies the wind direction in the hour range.
**WWCode:** Specifies the weather code in the time range.
**EffectiveCloudCover:** Specifies the amount of cloudiness in the hour range in octal units of measure.

## Technologies
Project is created with:
* PyCharm: 2021.3 
* Pandas: 1.3.4 (especially "corrwith")


	
## Setup
To run this project, just run the functions at the bottom of code and call "item_based_recommender". That's it!

## Developments 






