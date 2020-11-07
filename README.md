# Earthquake and Popular Venues Data Analysis of Turkey
IBM Data Science Specialization - Capstone Project


## Introduction
### Description & Discussion of the Background
Turkey is an earthquake populous country with 82 million inhabitants. It consists of 81 provinces. It is surrounded by the North Anatolia, Western Anatolia and Southeastern Anatolia earthquake zones. The diversity of landforms in Turkey, is a result of earth movement that shaped the terrain in the region for thousands of years. It has extinct volcanoes and earthquakes still occur frequently. In the north and east of the country, there are large fault lines that cause earthquakes today. The great Marmara earthquake that occurred on the North Anatolian Fault Line in 1999 caused the death of thousands of people. Although Turkey is a country of earthquakes, though it is also a tourist country. It is visited by millions of tourists from all over the world every year. There are even some foreign nationals to buy real estate in Turkey and make the trade. 

### Problem
A data analysis based on earthquake statistics and popular locations of each city will be found interesting by investors and consumers. Investors can carry out projects for places with less earthquake risk and invest in jobs where the type of business in those places is less intense. For regular person living in cities, they may want to buy and live in places that are less dangerous and at the same time close to social venues. Therefore, with a clustering study to be carried out by taking earthquake statistics based on a reasonable past (for example, 100 years) of each city, the regions with high or no earthquake risk can be determined. In addition, by comparing popular venues in these regions, the distinctiveness between regions can be revealed.

## Data
The data sources used in this study to solve the problem are as follows:

* From the __AFAD Earthquake Catalog page__, the statistics of the earthquakes that
occurred between 1920-2020 and whose magnitudes were between 4-10 according to
the Richter scale were taken in csv format with various filtering methods.

* With __OpenStreetMap__, the GeoJSON data needed for earthquake distribution and
maps showing clustered groups was provided. 

* With the __Foursquare API__, the type information of the most popular venues of the cities,
the latitude and longitude information of those places were obtained. 

* From __Wikipedia__ was taken Turkey's cities list. The latitude and longitude information
of the cities were obtained by querying them one by one with the help of Python __GeoPy__
Library.

