# MOD11-Data-Collection
Adam Gostinger <br/>
30 August 2023  

## Table of Contents
- [About](#about)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [Summary](#summary)
  
## About
This is a full web-scraping and data analysis project involving identifying HTML elements on a webpage, including ID and class attributes, and how to extract information via automated browsing with Splinter and HTML parsing with Beautiful Soup. These tools allow for scraping various types of information from websites. The scraping can be used to extract HTML tables and recurring elements, like multiple news articles or weather information on a webpage.  In this Challenge, I will be using these core skills: collecting data, organizing and storing data, analyzing data, and then visually communicating insights.  

## Getting Started
Jupyter Notebook is required to run this project as well as chrome driver, splinter, Pandas, matplotlib  and BeauitfulSoup.  

## Contributing
- <a href="https://www.github.com/jgrubb38/" target="_blank">Jennifer Grubb</a>  
- <a href="https://www.github.com/ryguy57/" target="_blank">Ryan Himes</a>  

## Summary
Part 1: Mars News Site Web-scraping.
In Part 1: The website <a href="https://static.bc-edx.com/data/web/mars_news/index.html" target="_blank">Mar's News</a> was analyzed using splinter, chrome driver and BeautifulSoup. The list of article titles and summary of the articles was extracted and placed into a dictionary and then appended into a Python list. 

Part 2: Mars Weather Web-scraping
In Part 2: The website <a href="https://static.bc-edx.com/data/web/mars_facts/temperature.html" target="_blank">Mar's Weather</a> was scraped using splinter, chrome driver and BeautifulSoup to pull in the table of weather data from Mars over a period of time. This data was added to a Python list and turned into a Panda's dataframe along with the extracted titles. 

The dataframe was grouped by Month to determine the average temperature and pressure by month based on the sample data from the website. The coldest months are Months 3 and 4 and Months 8 and 9 are the warmest months. Furthermore, Month 6 is the lowest pressure on Mars and Month 9 is the highest pressure month. Lastly, the daily minimum temperature was plotted on a line graph over the days elapsed to determine the length of a year on Mars based on the peak temperatures. A year on Mars appears to be about 675 days from the plot based on the peak to peak temperatures (according to NASA, a year on Mars is 687 earth days).





