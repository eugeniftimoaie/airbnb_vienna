# Vienna Airbnb Analysis
Analysis of Vienna AirBnB listings for 2019-2020

## Motivation
This project is part of Udacity's Data Science Nanodegree Program. Here we analyise Airbnb listings and calendar data published by http://insideairbnb.com. The CRISP-DM process is followed to perform statistical analysis examining the types and sizes of listings and listed prices throughout the year.

It asks and answers following business questions:
1. Where can we find the most listings in Vienna?
2. Which type and size have the listings?
3. Which are the cheapest and the most expensive districts in Vienna?
4. When is the most suitable time to rent an Airbnb appartment in terms of price and availability?
5. Is there a significant price difference between weekdays and weekends?

A blog post with the results can be found on following site: https://medium.com/@eugen.iftimoaie/5-insights-you-need-to-know-about-airbnb-in-vienna-3fb9c0766ef6

## Configuration & Installation
* Python 3.7 with libraries numpy, pandas, geopandas, scipy, matplotlib, seaborn, folium
* Jupyter Notebook

## File Manifest
* airbnb_vienna.ipynb - jupyter notebook with code and outputs of the analysis
* base_map_legend.py - python file with code for formatting legend of base map
* vienna/listings_det.csv - csv file with data of listings (http://insideairbnb.com/get-the-data.html | status: 19.11.2019)
* vienna/calendar.csv - csv file with daily availability and price data of listings (http://insideairbnb.com/get-the-data.html |status: 19.11.2019)
* vienna/neighbourhoods.geojson - geojson file with geographical data of Viennas' neighbourhoods (http://insideairbnb.com/get-the-data.html |status: 19.11.2019)

## Copyright and Licencing
This project is licensed under the terms of the MIT license

## Contact
Author: Eugen Iftimoaie
For questions feel free to contact me on my e-mail adress: eugen.iftimoaie@gmx.de
