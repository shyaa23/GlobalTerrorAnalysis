# Analysis on Global Terrorism Data

**1. Introduction**\n
This repository makes use of four dataset which are Global Terrorsm Database (GTD) from years 2013-2016; Poverty dataset, Population dataset, county information of US cities. The primary purpose of this repository is to analyze the terrorism accross United States. For this purpose, information of US population, poverty and city and county are cleaned and joined together as one dataset. 

**2. Data Cleaning and manipulation**\n

For the preprocessing purpose, different missing values coded as 9, -99 or blank are converted into N/A. Each of the dataset is sepertely cleaned and merged together according to common state name and city or county.

**3. Data Analysis and Exploration**\n
Once the data were merged, relationship among different variables were analyzed. Following are some questions that has been analyzed:

1. Plot of U.S showing each incident according to location, incorporating city's population size and poverty.

2. Plot of the number of incidents by month, according to type of incident as described by individual, and by claimed.

3. Relationships of population size and the three poverty variables to combined nkill and nwound. 

4. Relationships of population size and the three poverty variables to attacktype1_txt.

5. Relationship between attacktype1_txt the variable property and individual.
