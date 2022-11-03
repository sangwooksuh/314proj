# Progress Report 1


Group members: Kevin Yan, Sangwook Suh

We wish to participate in the Kaggle competition submission.

## Problem Domain & Statement

Airbnb is an increasingly popular platform to find temporary housing. The data can be used from both hosts and customers; hosts can determine what price to charge, and customers can see if a potential place they are looking for is a good price. We will use basic listing information, along with reviews, geographic data and any other information we can procure from web scraping.

**Problem Statement: How much should an Airbnb listing cost?**

## Scope

We may adjust scope features and / or assignend teammates depending on progress.

### Web Scraping 

* 1 feature: Kevin & Sangwook

* We will use python web scraping libraries and popular open source technology to scrape data from Airbnb.com. Since we are in STL, we will scrape data from this region, but may also potentially look in bigger cities such as NYC or Seattle for more data.

* If Web Scraping turns out to be infeasible, we will use datasets provided through [inside airbnb](http://insideairbnb.com/).  In this case, we will additionally implement SQL databases, or some other feature in place.

### Data Cleaning 

* 1 feature: Kevin

* As Airbnb does not provide a direct API, the data we get from scraping would probably need cleaning and reorganizing, according to good practices learned in class

### Data Visualization/Dashboarding 

* 1 feature: Sangwook

* We will provide a dashboard that will interactively display data of a particular listing in relation to other data in the dataset, so users can easily gauge different qualities of a dataset without inspecting all data.

## Timeline

**Web Scraping &rarr; Planning &rarr; Data Cleaning & Data Visualization &rarr; Prediction & Presentation** 

Data cleaning and visualization seem to be dependent on web scraping, so we might have to get that out of the way first. Both teammates will work on this together, exploring different tools and approeaches. If we don’t make meaningful headway in 3~4 weeks, we will pivot to using precompiled datasets from [inside airbnb](http://insideairbnb.com/). If we have to do this, we will add aditional features to compensate.

Once we can effectively get our data from scraping, then we will discuss how to clean or normalize the data so that it is optimal for visualization & prediction. This would mean defining structure, knowing what datatypes would go in what columns, agreeing on column names & indexes, etc. Once we have a written specifications planned out, we can split up and begin workinn on our individual features, Kevin for Data Cleaning, Sangwook for Data Visualization/Dashboarding. Finally, we can use the data to make predictions and present the results to the class.

## Anticipated Roadblocks/Questions

* How do we start web-scraping when it’s the third to last module of the semester?
* Could last year’s later modules be released earlier to get a head start planning & implementing the project?
* What exact features from Airbnb are going to be available to us through web scraping?
* Will there be enough usable features that can help us make a prediction in something that we are interested in?
* How wide of a scope do we want? Do we want to hone in on one specific city? Country? Continent?


