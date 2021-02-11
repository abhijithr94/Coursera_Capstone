# IBM Data Science Capstone

## Introduction

This project will show how data science via IBM Watson Studio and Jupyter notebook can be used to derivate, extract and post results.

## Segmenting and clustering Neighborhoods in Toronto

Using Toronto neighborhood Wikipedia data, we are going to explore, segment, and cluster the neighborhoods in the city of Toronto based on the postalcode and borough information.

### Structured notebook to display a dataframe with specific columns

1. Using BeautifulSoup package to parse the Wikipedia html
2. After clean up, the dataframe will consist of three columns: PostalCode, Borough, and Neighborhood
![PostalCode_Neighborhood](PostalCode_Neighborhood.PNG)

3. More than one neighborhood can exist in one postal code area, hence combining them into one row separated with a comma
4. Using .shape to display the size of the dataframe
5. Adding in latitude and longitude to the dataframe
6. Segmenting Toronto using Foursquare API
	- Displaying a map of Toronto Neighborhoods
	- Displaying a map of Toronto Borough
7. Clustering Toronto using K-Means
	- Displaying a map of the 5 clusters created
	- The five clusters shown in the map above
