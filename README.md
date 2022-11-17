# **EDA with Time Series ( Tesla Stock)**

Tesla also produces three energy storage products, the Powerwall home battery, the Powerpack commercial-scale battery, and Megapack, which is designed for utility-scale installations.

In 2016, Tesla became the world’s first vertically-integrated sustainable energy company with the acquisition of SolarCity, the leading provider of solar power systems in the United States, and in 2017 released Solar Roof – a beautiful an affordable energy generation product.


![App Screenshot](https://img.money.com/2021/05/Investing-How-To-Buy-Tesla-Stock.jpg)

## Methodology:

    1. Description
    2. Objective Statement
    3. Prerequisite
    4. EDA

Basic sentiment analysis of comments on a youtube video using a builtin python package "TextBlob Sentiment Analyser".
### Objective:
The objective is to analyse the stocks of Tesla co and perform data visualization for better understanding.

* Date time index
* Extract Date feature
* Time resampling
    1. Year end Frequency (rule = 'A')
    2. Quaterly start frequency (rule = 'QS')
    3. Business End frequency (rule = 'BA')
    4. Business Quater start frequency (rule = 'BQS')
* visualization
* Rolling


## Prerequisite :
_pandas package :_

> $ sudo pip install pandas

_pandas_datareader package :_

> $ sudo pip install pandas_datareader

_matplotlib package :_

> $ sudo pip install matplotlib


 ### Full report of this project: [Time-Series](https://github.com/L-VinayKumar/EDA-with-Time-Series-/blob/main/Time_series_EDA/Tesla_data.ipynb)

## Time Resampling:
    * Year end Frequency
![Logo](https://github.com/L-VinayKumar/EDA-with-Time-Series-/blob/main/Time_series_EDA/Year-end-Freq.PNG?raw=true)
    

    * Business Quater start frequency
![Logo](https://github.com/L-VinayKumar/EDA-with-Time-Series-/blob/main/Time_series_EDA/Business-quater-start-Freq.PNG?raw=true)

## Visualization:
    * Tesla Stock Open Price with 10 days 'Rolling'
![Logo](https://github.com/L-VinayKumar/EDA-with-Time-Series-/blob/main/Time_series_EDA/10-days_Rolling.PNG?raw=true)
