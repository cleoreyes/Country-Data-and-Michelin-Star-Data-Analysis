Data Documentation:

  The data we used was pulled from Kaggle. 

  For out data on Michelin Starred Restaurants around the world we used this data set colleected by NGSHIHENG:
https://www.kaggle.com/datasets/ngshiheng/michelin-guide-restaurants-2021 
This data set contains information about each Michelin rated restaurant like their location, price, amenitites, and ways to contact the restaurant. 

  For our data on each country we used this global information data set collected by NIDULA ELGIRIYEWITHANA:
https://www.kaggle.com/datasets/nelgiriyewithana/countries-of-the-world-2023/data
This data set contains information about each country. These data points include GDP, land mass, population, birth rate, life expectancy, and many more. 


  Our final data set contains 7 columns and 204 rows. Our columns are the following: Country, GDP, Population, Land Area (Km2), Minimum wage, Total Number of Stars, and Price Rating. Each of these columns are for each individual country. For columns Country, GDP, Population, Land Area(Km2), and Minimum wage we just used data from the country data set. For Total Number of Stars we calculated how many stars each country has collected through all of the restaurants located in that country. For Price Rating we created 4 different categories of Cheap, Affordable, Pricey, and Premium. We took the average of the prciing based on how many $ symbols each restaurant had. One $ referring to cheap, 2 to Affordable, 3 to Pricey, and 4 to Premium. 
  
Some columns have missing values:
  Country: 0
  Total Number of Stars: 0 
  GDP: 11
  Population: 10 
  Land Area(Km2): 10
  Minimum wage: 54
  Price Rating: 161
  
  The reason for some missing data is because that data has not or can not be collected at the current momment. This would apply more to third world countries where data collection is hard to do. The reason for the Price Rating to have so many missing values is because a large portion of countires do not have Michelin rated restaurants so no data can be calculated. 