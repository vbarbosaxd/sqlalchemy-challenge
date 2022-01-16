# SQLAlchemy Challenge
The purpose of this assignment was to analyze the climate of Honolulu, Hawaii using SQL, SQLAlchemy, Pandas, Matplotlib, and Flask.

This was done in two parts:  Climate Analysis and Exploration (using SQLAlchemy ORM queries, Pandas, and Matplotlib) and Climate App (using a Flask API to generate a website).

![image](https://user-images.githubusercontent.com/92385042/149673071-c508e5e8-71c1-4970-ac16-1b132778cad1.png)

## Part 1: Climate Analysis and Exploration
For this portion, I used Python and SQLAlchemy to do basic climate analysis and data exploration of my climate database.

I did a precipitation analysis by quering the preceding 12 months of data, transforming it into a Pandas DataFrame and then plotting the results.

![image](https://user-images.githubusercontent.com/92385042/149673074-788d1baf-3c1f-44e2-96bf-26b9fe857e39.png)

Then, I did a station query to find the most active weather stations in order to accurately calculate the lowest, highest, and average temperature. Then, based on that information, I generated a histogram.

![image](https://user-images.githubusercontent.com/92385042/149673161-872b9562-9862-43ab-bee2-b0679d7a767a.png)

## Part 2: Climate App
For this portion, I designed a basic interactive Flask application that took the user to different routes, including a homepage, precipitation information, weather station information, temperature observations, and temperature given a start-end date range.  
