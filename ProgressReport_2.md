# Progress Report 2

Group members: Kevin Yan, Sangwook Suh


## Title: Web Scraping


**As a** traveller looking for short term housing,

**I want to** know Airbnb housing prices in the area I am visiting,

**so that** I can judge whether a property is reasonably priced or not.



### Scenario 1: Short term housing data on a specific area of interest is needed

**Given** that a traveler has a target city or location in mind,

**and** know how many people are travleling,

**and** have an approximate date range,

**when** they set the location, date, and number of travelers,

**then** they should get the relevant data as a .csv file.


 
### Scenario 2: Housing data on a set date range is needed

**Given** that the traveler doesn’t have a specific location in mind,

**and** knows when they are free to travel,

**when** they set the dates of travel,

**then** they should get the data of relevant properties as a .csv file.




## Title:  Data Cleaning

**As a** data scientist exploring Airbnb housing data,

**I want to** to be able to clean and normalized the scraped data,

**so that** I can easily manipulate it for analysis.


### Scenario 1: Data should be normalized

**Given** freshly-scraped data,


**and** the data is very messy and unorganized,


**when** the user uses the function,


**then** the data should be returned normalized.


### Scenario 2: Addresses should be standardized


**Given** freshly-scraped data,


**and** the addresses of the Airbnb’s are inconsistent,


**when** the user uses this function,


**then** the addresses should be cleaned,


**and** standardized in a way so that they can all be analyzed.


## Title: Data Visualization/Dashboarding

**As a** traveler or data scientist interested in an accessible summary of Airbnb housing data,

**I want** visualize certain features of the Airbnb houses,

**so that** I can understand trends in housing prices.

### Scenario 1: Should be able to understand relationship between various features

**Given** clean data of the Airbnb properties,

**and** has certain features of interest,

**when** the user selects the features of interest,

**then** scatter plots showing the correlation of the the features should be visualized. 


### Scenario 2: Should be able to visualize prices of various houses


**Given** cleaned data of the Airbnb houses,


**and** the prices of the houses are cleaned,


**when** the user uses this function,


**then** the prices of all the houses should be visualized,


**and** analyzable in a way to easily compare the prices of houses in a certain area.


### Scenario 3: Should be able to visualize predicted prices by change of a feature


**Given** cleaned data of the Airbnb houses,


**and** a feature of interest,


**when** the user uses this function,


**then** the scatterplot of feature vs price along with a plot of the linear model should be visualized.




