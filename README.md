# Python-for-data-analysis-2-

## Immoscout24 - Apartment rental offers in Germany

### Introduction
I live in Berlin. Berlin is a big city that used to have the reputation of having cheap rents. While other cities are certainly still much more expensive, rents in Berlin have risen significantly. I am interested in what rents are like in German cities. 
Rental offers data set was scraped from a private person from Immoscout24. The data set contains information about apartment rental offers in Germany, including their characteristics, e.g. location, costs, building fabric & energy certificate, equipment. At a given time, all available offers were scraped from the site and saved. This process was repeated three times, so the data set contains offers from the dates 2018-09-22, 2019-05-10 and 2019-10-08.
Because of scraping, the data belongs to [Immobilienscout24](www.immobilienscount24.de) and is for research purposes only. The data was created with R. 
I also did a time series analysis to prepare my data for forecasting.

### Objective
I would like to find out more information about the housing offers in Germany via the portal Immoscout24. The task is to do an initial data and exploratory
analysis of the data to gain insights and help people who are looking for housing by recommending actions. 

### Key Questions
Clarifying questions:
* Which city have most expensive flats?
* Where can people live most cheaply? Where are the 10 affordable flats?
* Which characteristics do expensive and cheap flat have?
* Where are the most and the fewest flats offer?

Funneling questions:
* Are flats with almost the same characteristics in the same price level? 
* Does the city district have an influence on the price? baseRent city district
* Are renovated flats in the same price range as first time use flats? 
* Are bigger flats more expensive than smaller flats? 
* Do the number of plat offers in a region/city have an influence on the price?

### Data
I’ll work with a scraped dataset from a private person:

* [Immoscout24 Data Set](https://www.kaggle.com/corrieaar/apartment-rental-offers-in-germany)
* [Germany Federal states geojson](http://opendatalab.de/projects/geojson-utilities/)

For the time series analyze I’ll work with a dataset from [Quandl’s website](https://data.nasdaq.com/search?query=germany):

* [Inflation Rates](https://data.nasdaq.com/data/RATEINF-inflation-rates)


### Folder organization
01 Project management: This folder contains all documents related to the project, e.g. a project plan with timetable, a budget, signed contracts and generally all important documents related to the organisation of the project.

02 Data: This folder contains all the data sets used in the project.

03 Scripts: This folder contains my notebooks.

04 Analysis: This folder contains all the results I create during my analysis.

05 Sent to client: This folder contains all the final results I would have sent to the client.
