# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
I chose London UK for my project of statiscal modelling with python. My goal is to use APIs from CityBike and draw the number of free bikes at each bike station within the city of London. Then, use APIs from Foursquare and YELP to collect nearby venues around each bike station. Finally I will need to state if the venues have a relationship on the number of free bikes at each station.  

## Process
#### STEP ONE : I used API from CityBike website and acquired bike station data for London. There are a total of 799 bike docking stations located in the city. I parsed throug the result and decided to keep the address, coordinates and the number of free bikes of each station. 
 
#### STEP TWO : During step two, I need to extract venues from Foursquare and YELP. For foursquare API, I chose the number of theatre, restaurants and bars around each bike station. For YELP's API, playground, retaurant and entertainment venues were chosen. 

#### STEP THREE : I decided to use the information I extracted from YELP to combine them with CityBike. Afterwards, I used heatmap and seaborn visualization to try to find the strength of the relationship between the dependent variable, number of free bikes, and the other independeent variables, restaurants, theatre and playground. 


## Results
![](images/sns%20heatmap.png)
![](images/bikes%20vs%20restaurant.png)
![](images/bikes%20vs%20playground.png)
![](images/bikes%20vs%20entertainment.png)

## Challenges 
The challenging aspects of this projects are extracting venues with the information I want from the APIs, finding and plotting releveant infomration between the number of bikes and point of interests. 

## Future Goals
I will try my best to find the correlated variables between number of bikes and point of interests. I believe there are other factors that I have not considered. I would actually do some research about the city of London because I dive into finding the correlated variables. 