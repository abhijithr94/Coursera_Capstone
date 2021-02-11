# IBM Data Science Capstone

## Introduction

This project will show how data science via IBM Watson Studio and Jupyter notebook can be used to derivate, extract and post results.

## Segmenting and clustering Neighborhoods in Toronto

Using Toronto neighborhood Wikipedia data, we are going to explore, segment, and cluster the neighborhoods in the city of Toronto based on the postalcode and borough information.

### Structured notebook to display a dataframe with specific columns

1. Using BeautifulSoup package to parse the Wikipedia html
2. After clean up, the dataframe will consist of three columns: PostalCode, Borough, and Neighborhood
3. More than one neighborhood can exist in one postal code area, hence combining them into one row separated with a comma:

![PostalCode_Neighborhood](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/PostalCode_Neighborhood.PNG)

4. Using .shape to display the size of the dataframe:
![Dataframe_Size](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Dataframe_Size.PNG)

5. Adding in latitude and longitude to the dataframe:
![Geocoder_Location](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Geocoder_Location.PNG)

### Map visualization and K-Means Clustering
1. Segmenting Toronto using Foursquare API
	- Displaying a map of Toronto Neighborhoods:
	![Toronto_Neighborhood](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Toronto_Neighborhood.PNG)
	
	- Displaying a map of Toronto Borough:
	![Toronto_Borough](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Toronto_Borough.PNG)
	
2. Clustering Toronto using K-Means
	- Displaying a map of the 5 clusters created:
	![Toronto_Clustered](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Toronto_Clustered.PNG)
	
	- The five clusters shown in the map above are:
	
	-> First Cluster
	![First Cluster](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/First_Cluster.PNG)
	
	-> Second Cluster
	![Second Cluster](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Second_Cluster.PNG)
	
	-> Third Cluster
	![Third Cluster](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Third_Cluster.PNG)
	
	-> Fourth Cluster
	![Fourth Cluster](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Fourth_Cluster.PNG)
	
	-> Fifth Cluster
	![Fifth Cluster](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Fifth_Cluster.PNG)
