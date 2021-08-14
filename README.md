# Regional and Provincial covid-19 data scraper.
In this project we scrape the regional and provincial data (Daily New Cases/Deaths) in Morocco provided by the official website for Covid-19: www.covidmaroc.ma .

Historical covid-19 data for regions and provinces are hard to find or they are not easily collected. This repository contains the most comprehensive and up-to-date historical data for all regions and provinces in Morocco. 

![covidmaroc](/Covid-19.PNG)

To scrape data we perform the following tasks :

1-Get the source code of the website.

2-Extract tabular data from all PDFs in http://www.covidmaroc.ma/Pages/LESINFOAR.aspx 

3-Clean and filter the data

4-Convert the raw data to a data frame


## Running the scraper
In order to run the scraper, you will need to download and execute this [jupyter notebook](https://github.com/AmineAndam04/Regional-and-Provincial-covid-19-data/tree/main/Code-python)


Requirements :Pandas,Numpy,requests,BeautifulSoup and PyPDF2 


## Files
NC Province.xlsx : Daily New Cases in each province. Starts from 03/09/2020

ND Province.xlsx : Daily New Deaths  in each province. Starts from 03/09/2020

NC Region.xlsx : Daily New Cases in each region. Starts from 03/09/2020

ND Region.xlsx : Daily New Deaths in each region. Starts from 03/09/2020

## Regions and Provinces in Morocco 
Our files contain covid-19 data for the 12 regions and 75 provinces of Morocco. For more details go to [Administrative divisions of Morocco]( https://en.wikipedia.org/wiki/Administrative_divisions_of_Morocco#Current_administrative_divisions)
