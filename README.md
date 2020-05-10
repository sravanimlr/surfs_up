# surfs_up
Working with SQLAlchemy to analyze weather data to predict the success of a business. 

## Project Overview
 The weather data for Oahu, an island in Hawaii, was analyzed through SQLalchemy methods. The Sqlite file was loaded through Jupyter Notebook and the describe function was used to analyze statistics. The weather data was analyzed to ensure that when a business is opened, that weather problems will not cause the business to fail. 
## June Temperatures
 The June temperature data was gathered for years 2010-2017. There were 1700 data points analyzed for percentiles based on standard deviation along with max, min, mean etc. June temperatures followed a trend of mid 70s and a max of 85. The histogram shows a distribution of temperatures more concentrated in the 75 and 80 range. In the 7-year period, the temperatures did not vary much and followed a pattern. June is an ideal time to spend time outside, thus the business might notice an increase during June and summer months specifically. 
 ## June Statistics 
![JuneStats](June Stats.png)
## June 2010-2017 Temperatures Histogram 
![JuneTempsHistogram](June Temps Histogram.png)

## December Temperatures 
 Similarly, 2017-2017 years were analyzed for December temperatures. 1,517 data points were analyzed for mean, mean, min, and percentiles based on standard deviation. The mean temperature for December was 71, with a min of 55 and max of 80. The distribution of temperatures was between 65-75 based on the histogram. December is winter season and may cause a shortage of visitors to the business location. 
 ## December Statistics 
![DecStats](Dec Stats.png)
## December 2010-2017 Temperatures Histogram 
![DecTempsHistogram](Dec Temps Histogram.png)

Both June and December months followed their seasonal patterns for temperatures, thus it can be seen that June months favor higher temperatures as opposed to that of December. 

## Recommendations 
 Along with temperature, it would be a good idea to include precipitation data. Precipitation data was analyzed on its own during this project, but it will strengthen weather analysis if temperature and precipitation were combined. Also, it would be beneficial to take wind speed and humidity into account. Given this is a specific region in Hawaii, adding more variables will allow a specific analysis to be made. If the project becomes broader and focused on multiple countries or regions, then, snow amount will become crucial to analyze. If this project is used as a tool to speculate and predict amount of people that would visit a business, then all weather patterns will become important to analyze. Lastly, regions that follow day light savings time changes should be monitored for sunrise and sunset times as the day light changes can affect the length of a day in some months. Overall, weather analysis can be specific or broad based on the needs of a project, thus it is important to consider all variables when creating analyses.  
