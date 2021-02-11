# IBM Data Science Capstone

## Introduction

This project will show how data science via IBM Watson Studio and Jupyter notebook can be used to derivate, extract and post results.

## Segmenting and clustering Neighborhoods in Toronto

Using Toronto neighborhood Wikipedia data, we are going to explore, segment, and cluster the neighborhoods in the city of Toronto based on the postalcode and borough information.

### Structured notebook to display a dataframe with specific columns

1. __Using BeautifulSoup package to parse the Wikipedia html__
2. __After clean up, the dataframe will consist of three columns: PostalCode, Borough, and Neighborhood__
3. __More than one neighborhood can exist in one postal code area, hence combining them into one row separated with a comma:__

![PostalCode_Neighborhood](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/PostalCode_Neighborhood.PNG)

4. __Using .shape to display the size of the dataframe:__

![Dataframe_Size](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Dataframe_Size.PNG)

5. __Adding in latitude and longitude to the dataframe:__

![Geocoder_Location](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Geocoder_Location.PNG)

### Map visualization and K-Means Clustering
1. __Segmenting Toronto using Foursquare API__
	- Displaying a map of Toronto Neighborhoods:
	![Toronto_Neighborhood](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Toronto_Neighborhood.PNG)
	
	- Displaying a map of Toronto Borough:
	![Toronto_Borough](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Toronto_Borough.PNG)
	
2. __Clustering Toronto using K-Means__
	- Displaying a map of the 5 clusters created:
	![Toronto_Clustered](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Toronto_Clustered.PNG)
	
	- The five clusters shown in the map above are:
	
	-> _First Cluster_
	![First Cluster](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/First_Cluster.PNG)
	
	-> _Second Cluster_
	![Second Cluster](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Second_Cluster.PNG)
	
	-> _Third Cluster_
	![Third Cluster](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Third_Cluster.PNG)
	
	-> _Fourth Cluster_
	![Fourth Cluster](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Fourth_Cluster.PNG)
	
	-> _Fifth Cluster_
	![Fifth Cluster](https://github.com/abhijithr94/Coursera_Capstone/blob/main/Results/Fifth_Cluster.PNG)
