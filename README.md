Introduction
This project involves web scraping data related to Mars from two different sources. In the first part, we scrape news articles from the Mars news site, and in the second part, we scrape and analyze Mars temperature data.

Part 1: Scrape Mars News Articles
Objective:
Use automated browsing to visit the Mars news site and extract the titles and preview text of news articles.

Implementation:

Automated browsing is implemented using a web browser automation tool.
The Beautiful Soup library is used to create a Beautiful Soup object for extracting text elements from the website.
Titles and preview text of news articles are stored in Python dictionaries, and all dictionaries are stored in a Python list.
The results are printed in the Jupyter Notebook.
Part 2: Scrape and Analyze Mars Weather Data
Objective:
Use automated browsing to visit the Mars Temperature Data Site and extract temperature data. Analyze the data to answer specific questions.

Implementation:

Automated browsing is implemented to visit the Mars Temperature Data Site.
The Beautiful Soup library is used to scrape data from the HTML table.
The scraped data is assembled into a Pandas DataFrame with columns representing various parameters.
The data types of each column are examined and converted as necessary (datetime, int, or float).
Data analysis is performed to answer specific questions:
Number of months on Mars
Number of Martian days worth of data
Coldest and warmest months on Mars
Months with the lowest and highest atmospheric pressure on Mars
Approximate number of terrestrial days in a Martian year
The DataFrame is exported to a CSV file for further use.
Code Organization
part_1_mars_news.ipynb: Jupyter Notebook for scraping and analyzing Mars news articles.
part_2_mars_weather.ipynb: Jupyter Notebook for scraping and analyzing Mars temperature data.
Instructions
Run the Jupyter Notebooks (part_1_mars_news.ipynb and part_2_mars_weather.ipynb) to execute the code and perform the analysis.
Review the printed results and visualizations within the Notebooks.
Optionally, share the results with others by exporting the data to a CSV file (mars_weather_data.csv).
Feel free to explore, modify, and extend the code to further analyze and visualize Mars-related data.
