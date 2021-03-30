# somnathchouwdhury-weather-analysis-clusteing-using-k-means-algorithm-machine-learning


we will learn how to perform k-means clustering using scikit-learn in Python.

you can download the datasets from below link:
https://drive.google.com/file/d/1ydL59tlxKLFoZUUmx0OIlS6VUF2wuDE-/view?usp=sharing

make sure to keep csv file and python code in the same folder or change the location accordingly
About the dataset:

Weather Data Description

The weather dataset comes from the same source as the daily weather dataset that we used in the decision tree based classifier notebook. The main difference between these two datasets is that the minute weather dataset contains raw sensor measurements captured at one-minute intervals. Daily weather dataset instead contained processed and well curated data. The data is in the file minute_weather.csv, which is a comma-separated file.

As with the daily weather data, this data comes from a weather station located in San Diego, California. The weather station is equipped with sensors that capture weather-related measurements such as air temperature, air pressure, and relative humidity. Data was collected for a period of three years, from September 2011 to September 2014, to ensure that sufficient data for different seasons and weather conditions is captured.

Each row in minute_weather.csv contains weather data captured for a one-minute interval. Each row, or sample, consists of the following variables:

    rowID: unique number for each row (Unit: NA)
    hpwren_timestamp: timestamp of measure (Unit: year-month-day hour:minute:second)
    air_pressure: air pressure measured at the timestamp (Unit: hectopascals)
    air_temp: air temperature measure at the timestamp (Unit: degrees Fahrenheit)
    avg_wind_direction: wind direction averaged over the minute before the timestamp (Unit: degrees, with 0 means coming from the North, and increasing clockwise)
    avg_wind_speed: wind speed averaged over the minute before the timestamp (Unit: meters per second)
    max_wind_direction: highest wind direction in the minute before the timestamp (Unit: degrees, with 0 being North and increasing clockwise)
    max_wind_speed: highest wind speed in the minute before the timestamp (Unit: meters per second)
    min_wind_direction: smallest wind direction in the minute before the timestamp (Unit: degrees, with 0 being North and inceasing clockwise)
    min_wind_speed: smallest wind speed in the minute before the timestamp (Unit: meters per second)
    rain_accumulation: amount of accumulated rain measured at the timestamp (Unit: millimeters)
    rain_duration: length of time rain has fallen as measured at the timestamp (Unit: seconds)
    relative_humidity: relative humidity measured at the timestamp (Unit: percent)
