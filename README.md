# PyBer_Analysis

## Project Overview
A ridesharing app company called PyBer has tasked me with creating a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. The goal is to show how the data differs by city type and how those differences can be used by decision-makers at PyBer. 
Deliverable 1: A ride-sharing summary DataFrame by city type
Deliverable 2: A multiple-line chart of total fares for each city type

## Resources
-Data Source: City_Data.csv, Ride_Data.csv, PyBer_Challenge_starter_code.ipynb
-Software: Matplotli, Python, Visual Studio Code, Anaconda, Jupyter Notebook, Pandas

## Analysis of Data
Initially data was separated into three new datasets: one for urban areas, one for suburban areas, and one for rural. This initial separation revealed differences and were obvious when charted in a scatter plot:

![PyBer Scatter](https://user-images.githubusercontent.com/108022219/187552908-564f1def-4429-414c-8e02-12dc6964141e.png)

After analyzing the data, it is clear that rural users pay far higher fare rates than urban users, however urban users are much higher in the frequency of use. Majority of the fares are coming from urban users.

![Pyber Summary](https://user-images.githubusercontent.com/108022219/187553287-8d42e66f-f1b8-43f2-a926-7e3a4747e89c.png)

## Results and Summary
The analysis shows the disparity between urban areas, suburban areas, and rural areas.  The traveling distances and popualation of users within each area impact fare prices, while city trips are likely short and therefore less expensive,the rural are trips are longer. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/108022219/187553857-c3f72bad-b9c9-4bca-806e-fc5b571cf6ec.png)
