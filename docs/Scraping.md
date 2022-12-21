# Scraping
In this module, available cities and countries to scrape can be found, and then their data can actually be scraped.
All the data is scraped from http://insideairbnb.com/get-the-data
## 1. get_cities() and get_countries()
These two functions operate essentially in the same way: they both print a list of scrapable places. 

- get_cities() prints a list of all available cities that can be scraped 

- get_countries() prints a list of all available counties that can be scraped



## 2. get_city_data(city) and get_country_data(country)
These two functions also operate very similarly, both returning a freshly-scraped dataframe from the specified place (must be a String)

- get_city_data(city) returns a scraped dataframe containing all the AirBnB listings in that city
  - *Example:* get_city_data("amsterdam")
- get_country_data(country) returns a scraped dataframe containing all the AirBnB listings in that country
  - *Example:* get_country_data("greece")
