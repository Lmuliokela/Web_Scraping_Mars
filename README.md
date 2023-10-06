# Web_Scraping_Mars

## Description

**Description:** The task for this challenge was as follows - You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.
As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.
This new assignment consists of two technical products. You will submit the following deliverables; Deliverable 1: Scrape titles and preview text from Mars news articles and Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

---

## Dependencies

**Deliverable 1**

Import Splinter and BeautifulSoup

from splinter import Browser

from bs4 import BeautifulSoup as soup

**Deliverable 2**

Import relevant libraries

from splinter import Browser

from bs4 import BeautifulSoup as soup

import matplotlib.pyplot as plt

import pandas as pd

import numpy as np

---

## Part 1 - Scrape Titles and Preview Text from Mars News

- Used automated browsing to visit the Mars news site. Inspected the page to identify which elements to scrape.
- Created a Beautiful Soup object and used it to extract text elements from the website.
- Extracted the titles and previewed text of the news articles that I scraped. Stored the scraping results in Python data.

---

## Part 2 - Scrape and Analyze Mars Weather Data

- Used automated browsing to visit the Mars Temperature Data Site. Inspect the page to identify which elements to scrape.
- Created a Beautiful Soup object and use it to scrape the data in the HTML table.
- Assembled the scraped data into a Pandas DataFrame.
- Examined the data types that are currently associated with each column.
- Analyzed the dataset by using Pandas functions to answer some valid questions.
- Exported the DataFrame to a CSV file.


