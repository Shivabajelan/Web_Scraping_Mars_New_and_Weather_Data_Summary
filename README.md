# Web_Scraping_Mars_New_and_Weather_Data_Summary

#### This project focused on extracting and analysing Mars news articles and weather data from websites using web scraping techniques.

## Overview
### The goal of this project was to:

#### 1.Scrape titles and preview text from Mars news articles.
##### 2.Scrape and analyse Mars weather data in an HTML table.
## Tools and Technologies
#### Python
#### Jupyter Notebook
##### Beautiful Soup
##### Splinter
##### Pandas
# Project Structure
## Part 1: Mars News Scraping
#### 1.Used automated browsing with Splinter to visit the Mars news site.
#### 2.Created a Beautiful Soup object to parse the HTML content.
#### 3.Extracted the titles and preview text of the news articles.
#### 4.Stored the scraping results in a list of dictionaries with 'title' and 'preview' keys.
#### 5.Printed the list in the Jupyter Notebook.
#### 6.Stored the scraped data in a JSON file for easier sharing if needed in future.
## Part 2: Mars Weather Data Scraping and Analysis
#### 1.Used automated browsing with Splinter to visit the Mars Temperature Data Site.
#### 2.Created a Beautiful Soup object to scrape the data in the HTML table.
#### 3.Assembled the scraped data into a Pandas DataFrame with appropriate column headings.
#### 4.Examined and cast the data types to appropriate datetime, int, or float data types if necessary.
#### 5.Analysed the dataset to answer questions related to Martian months, days, temperature, and atmospheric pressure.
#### 6.Visualised the results using bar charts and line plots.
#### 7.Exported the DataFrame to a CSV file.
# Conclusion
##### This project demonstrated the ability to effectively use web scraping techniques to collect and analyze data from Mars-related websites. The findings provide valuable insights into Martian months, days, temperature, and atmospheric pressure.
