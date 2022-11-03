# Progress Report 2

Group members: Kevin Yan, Sangwook Suh

## Title: Returns and exchanges go to inventory.


**As a** store owner,


**I want to**  add items back to inventory when they are returned or exchanged,


**so that**  I can track inventory.


### Scenario 1: Items returned for refund should be added to inventory.


**Given** that a customer previously bought a black sweater from me


**and** I have three black sweaters in inventory,


**when** they return the black sweater for a refund,


**then** I should have four black sweaters in inventory.

### Scenario 2: Exchanged items should be returned to inventory.


**Given** that a customer previously bought a blue garment from me


**and** I have two blue garments in inventory


**and** three black garments in inventory,


**when** they exchange the blue garment for a black garment,


**then** I should have three blue garments in inventory


**and** two black garments in inventory.


## Title: Web Scraping


**As a** traveller looking for short term housing


**I want to** know Airbnb housing prices in the area I am visiting,


**so that** I can judge whether a property is reasonably priced or not.



### Scenario 1:

**Given**

**and**

**and**

**when**

**then**


### Scenario 2: 

* We will use python web scraping libraries and popular open source technology to scrape data from Airbnb.com. Since we are in STL, we will scrape data from this region, but may also potentially look in bigger cities such as NYC or Seattle for more data.

* If Web Scraping turns out to be infeasible, we will use datasets provided through [inside airbnb](http://insideairbnb.com/).  In this case, we will additionally implement SQL databases, or some other feature in place.


## Feature 2: Data Cleaning 

* As Airbnb does not provide a direct API, the data we get from scraping would probably need cleaning and reorganizing, according to good practices learned in class


## Feature 3: Data Visualization/Dashboarding 

* We will provide a dashboard that will interactively display data of a particular listing in relation to other data in the dataset, so users can easily gauge different qualities of a dataset without inspecting all data.


