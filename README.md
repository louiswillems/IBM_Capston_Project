# IBM Capston Project

For this final assignment, we will explore and cluster the neighborhoods in Montréal. For that, we will compare the data from Foursquare API with data of nearby venues from Google Maps API. We want to know which API give us better information about places in Montréal, QC, Canada.


Data Sources Used in this project:
- Postal codes in Montréal: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_H
- Google Geocoding API
- Foursquare API
- Google PLaces API


## 1. Introduction

For this problem, we need to have experience in cleaning data, working with API’s and data mining (clustering). 

We will scrape the Wikipedia page and wrangle the data, clean it, and then read it into a pandas dataframe so that it is in a structured format like the Toronto dataset (Week 3) but the structure is not the same:

- Montréal: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_H
- Toronto: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

For this project, we will need to work with Google Maps API. We will user Google Geocoding API in order the get the coordinates from Montréal and Google Places API in order to get all the places (radius=500). We will do the same process with the Foursquare API. 
Next, we will clusters Neighborhoods in Montréal with both informations and we will compare Foursquare with Google API data.


## 1. Data

We will segment and cluster the neighborhoods in the city of Montréal and compare Foursquare API with Google Maps API data. Like Toronto neighborhood data, a Wikipedia page exists that has all the information we need to explore and cluster the neighborhoods in Montréal.

Then, we will get the latitude and the longitude coordinates of each postal code in Montréal from Google Maps Geocoding API and we will merge our Wikipedia data with this Geocoding data.

Once the data is in a structured format, we will use the Foursquare API in order to cluster the neighborhoods in Montraél with K-Mean algorithm.

Next, we are going to start utilizing the Google Maps Place API to get venues for all neighborhoods in Montréal.

Finally, we will map, compare and analyse clusters Neighborhoods in Montréal with both informations and conclude.
