# **EDA with Time Series ( Tesla Stock)**

Tesla also produces three energy storage products, the Powerwall home battery, the Powerpack commercial-scale battery, and Megapack, which is designed for utility-scale installations.

In 2016, Tesla became the world’s first vertically-integrated sustainable energy company with the acquisition of SolarCity, the leading provider of solar power systems in the United States, and in 2017 released Solar Roof – a beautiful and affordable energy generation product.


![App Screenshot](https://img.money.com/2021/05/Investing-How-To-Buy-Tesla-Stock.jpg)
For full report of this project, please visit: [Sentiment Analysis](https://github.com/L-VinayKumar/YouTube-Sentiment-Analysis/blob/main/YouTube%20Sentiment-Analysis/Youtube-analysis.ipynb)
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
    1. year end Frequency (rule = 'A')
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


## Analyze the sentiments with stop words using WordCloud and Plotly.
    * positive comments
![Logo](https://github.com/L-VinayKumar/YouTube-Sentiment-Analysis/blob/main/YouTube%20Sentiment-Analysis/Positive_Comments.PNG?raw=true)
    

    * Top 20 Most-Frequent Emojis
![Logo](https://github.com/L-VinayKumar/YouTube-Sentiment-Analysis/blob/main/YouTube%20Sentiment-Analysis/Top%2020%20Emojis.PNG?raw=true)