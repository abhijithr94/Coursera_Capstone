# __IBM Data Science Capstone Project__

## Table of Contents
1. Background
2. Business Problem
3. Overview of Data

## 1. Background
Vancouver, a bustling west coast seaport in British Columbia, is among Canada’s densest, most ethnically diverse cities known for its art and scenery. With a population of over 2.5 million, there are more than 200 ethnic groups in the country, making up more than 16 per cent of the total population. South Asians account for a quarter of all visible minorities in Canada, or four per cent of the total population. South Asians have lived in the Vancouver region since the late 19th century; at first, mainly working in the forestry industry. After an initial first wave of immigration during the early 20th century, government policies aimed at curtailing immigration from the Indian subcontinent resulted in a populated stagnation through the 1950s. At that time, the relaxing of racial and national immigration restrictions by the federal government initiated a new wave of immigration into Vancouver and has continued into the present day. The vast majority of South Asians in Greater Vancouver and in adjacent cities are Punjabi Sikhs (Indians), differing greatly from the diverse ethnic and religious composition of South Asians in Canada. A lot of Punjabi Sikhs now own and run their very own restaurants in and around parts of Vancouver area focusing on various cuisines of the Indian subcontinent. The majority of these Indo-Canadian restaurants focus on the cuisine of northern India. In 2013 Alexandra Gill of The Globe and Mail wrote that in regards to area food critics the Indian restaurant scene was "a largely unknown dining landscape".

## 2. Business problem
Seeing the popularity of Indian food in Vancouver, the objective of the project is to use Foursquare API and clustering to best determine a neighborhood in Vancouver suitable to open an Indian restaurant. This will help business owners in deciding a convenient and apt location to open up a restaurant.

## 3. Overview of Data
This project will use Vancouver neighborhood data, Geolocation of Vancouver and Foursquare API to figure out which neighborhood will be an ideal location to open an Indian restaurant.

Vancouver Neighborhood Data - From Wikipedia - 
	https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_V
	
The postal codes shown in this site are the ones for British Columbia, these will be narrowed down to only the ones within the city of Vancouver

Geolocation of Vancouver - Will be determined via the Geocoder Package. 
	https://www.serviceobjects.com/blog/free-zip-code-and-postal-code-database-with-geocoordinates/
	
With the help of Postal Code Database, the following file in CSV will be then transformed into a dataframe for further analysis
	

Foursquare API - Using this to explore the various venues in and around Vancouver
