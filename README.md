# CaseStudy1_Matt_Paritosh
This is the case study 1 repository of Matt and Parish

Libraries

library(knitr): General purpose literate programing engine. Helps users to give better control of the output.

library(downloader): Provides a wrapper for the download files over HTTPS to different platform like Mac OS, Unix and Windows.

library(dplyr): This package help summarize tabular data, data aggregation including pipe operator

library(data.table): This package helps user to organize, view and access data. 

library(ggplot2): This is a plotting library in R. Can be used plottingand customizing the graphs. User can use to plot the map data too.

library(webshot): This package help user to take screenshots of wen page from R. 

library(kableExtra): This package simplifies the way to manipulate the HTML and LaTeX codes. Helps user to manipulate and built complex tables using simple syntax. 

library(maps): Maps library contains powerful function to plot maps. It contains lot of continents, countries, states and counties. 

library(mapdata): Another powerful map plotting contain more outlines with higher resolution outlines.

library(tidyverse): This package is designed to make easy to install and load core package for R. 

library(stringr): excellent package for data cleaning and preparation tasks.

library(dplyr): Very helpful package when performing exploratory data analysis and manipulation

library(viridis): viridis package provides color palettes to enhance the plots.


csv files used for analysis:
Brewries.csv: This csv file contains information of Breweries:
	Brew_ID: Unique identifier for Breweries
	Name : Name of the Breweries 
	City: Name of city where these Breweries are located
	State: State where these Breweries are located

Beers.csv: This csv file contains information on Beers:
	Name: Name of the Beers
	Beer_ID: Unique identifier for Beers
	ABV: Shows ABV value of the beer (Alcohol by volume)
	IBU: Shows IBU of the Beer (International Bitterness Unit)
  Brew_id: Brew_ID: Unique identifier for Breweries
  Style: Differentiate and categories of beers
  Ounces: measure of quantity of beer 

Variables used in this program:

Brewries: red Brewries.csv file to r

Beers: read beers.csv file to r

BrewCount: Number of breweries in each state

Beers_brew: This is data frame where beers.csv and Brewries.csv are merged using brewery_id/Brew_ID

totalna: have list of columns where NA were found during data cleanup effort.

totalna1: same as totalna, used for drawing pie chat. 

ABV: Data frame containing ABV value of beers in each state.

IBU: Data frame containing IBU value of beers in each state.

MedianABV: Median ABV value of beers in that state. 

MedianIBU: Median IBU value of beers in that state. 

ABV_IBU: data frame containing IBU and ABV info. 




