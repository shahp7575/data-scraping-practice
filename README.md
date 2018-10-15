# Web Scraping

-  Web scraping or web data extraction is data scraping used for extracting data from websites.
-  It is a form of copying, in which specific data is gathered and copied from the web, typically into a central local database or spreadsheet, for later retrieval or analysis.

-  This repository contains four python notebooks:
  1)  [practicing-scraping.ipynb](https://github.com/shahp7575/data-scraping-practice/blob/master/practing-scraping.ipynb) - This is my solution to the [w3resource](https://www.w3resource.com/python-exercises/web-scraping/index.php) web scraping exercise.
  2)  [scraping-tech-track-top-100-companies](https://github.com/shahp7575/data-scraping-practice/blob/master/scraping-tech-track-top-100-companies.ipynb) - This is scraping the [Tech Track top 100 companies](http://www.fasttrack.co.uk/league-tables/tech-track-100/league-table/). This is based off an amazing web scraping tutorial on [Medium](https://towardsdatascience.com/data-science-skills-web-scraping-using-python-d1a85ef607ed) by Kerry Parker.
  3)  [scraping-indeed-data-scientists.ipynb](https://github.com/shahp7575/data-scraping-practice/blob/master/scraping-indeed-data-scientists.ipynb) - This involves scraping indeed.com to find out whether MapReduce or Spark is more in demand for the position of data scientist. This is a part of a tutorial by [Jesse Steinweg-Woods](https://jessesw.com/Data-Science-Skills/)
  4) [scraping-pets-overstock.ipynb](https://github.com/shahp7575/data-scraping-practice/blob/master/scraping-pets-overstock.ipynb) - This notebook is my personal project of scraping the website pets.overstock.com. Based on the zip code entered, the program scrapes the data from the website and creates a .csv file with a list of all the cats along with their type, age, and their shelter name, town, state. Then it creates a bar chart to visualize which age of cats are present the most in that town.
  
  
  ## Getting Started
  
  ### Libraries required
  -  urllib
  -  bs4 (Beautiful Soup)
  -  requests
  -  csv
  -  json
  -  pickle
  -  re
  
  Libraries can be installed using ```pip```, the Python package manager.
  For example:
  
  ```pip install bs4```
