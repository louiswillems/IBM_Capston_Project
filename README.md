# Comparing information of places from neighborhoods in Montreal: Foursquare API vs. Google Places API


## 1. Introduction

For this final assignment, we will explore and cluster the neighborhoods in Montréal. For that, we will compare the data from Foursquare API with data of nearby venues from Google Maps API.

Business problem: We want to know which API give us better information about places in Montréal, QC, Canada.

For this project, we need to have an experience in cleaning data, working with API’s and data mining (clustering). 
We will need to work with Google Maps API and Foursquare API.More precisely, we will use Google Geocoding API in order the get the coordinates from Montréal and Google Places API in order to get all the places (radius=500). We will do the same process with the Foursquare API. 

Next, we will clusters Neighborhoods in Montréal with both informations and we will compare Foursquare with Google API data



## 1. Data

We will segment and cluster the neighborhoods in the city of Montréal and compare Foursquare API with Google Maps API data. Like Toronto neighborhood data, a Wikipedia page exists that has all the information we need to explore and cluster the neighborhoods in Montréal.

We will scrape the Wikipedia page, wrangle the data, clean it, and then read it into a pandas dataframe so that it is in a structured format like the Toronto dataset (Week 3) but the structure is not the same:

- Montréal: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_H
- Toronto: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

Then, we will get the latitude and the longitude coordinates of each postal code in Montréal from Google Maps Geocoding API and we will merge our Wikipedia data with this Geocoding data.

Once the data is in a structured format, we will use the Foursquare API in order to cluster the neighborhoods in Montraél with K-Mean algorithm.

Next, we are going to start utilizing the Google Maps Place API to get venues for all neighborhoods in Montréal and we will also cluster with K-means.

Finally, we will map, compare and analyse clusters Neighborhoods in Montréal with both informations and conclude.

Data Sources Used in this project:
- Postal codes in Montréal: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_H
- Google Geocoding API
- Foursquare API
- Google PLaces API
