### web-scraping

# Resources
- Data Source: 
-[Mars News](https://static.bc-edx.com/data/web/mars_news/index.html)

-[Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) 
- Software: Python 3.9.13, Jupyter Notebook.

# Part 1: Scrape Titles and Preview Text from Mars News

File location: [web-scraping-codes/part_1_mars_news.ipynb](web-scraping-codes/part_1_mars_news.ipynb)

# Part 2: Scrape and Analyze Mars Weather Data

File location: [web-scraping-codes/part_2_mars_weather.ipynb](web-scraping-codes/part_2_mars_weather.ipynb)

With using Splinter, you can see the Mars Temperature Data Site, and scraped the data using Beautiful Soup  to create a Pandas Dataframe that included information about Mars (terrestrial date, sol, ls, month, min temperature, and pressure). 

Analysis: 

Utilizing the data we scrapped, we answered the following questions:

How many months there are on Mars? 
How many terrestrial days exist in a Martian year? A visual estimate within 25% was made.
How many Martian days' worth of data are there?
On avarage higest and lowest temperature and which month?
On avarage higest and lowest atmospheric pressure has and which month? 
 

Exported the DataFrame into a CSV file [Mars_weather_data](web-scraping-codes/Mars_weather_data.csv). 





