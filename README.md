# Web Scraping and Data Analysis Project

## Project Overview
This project involves scraping Mars news articles and weather data, followed by data analysis and visualization. The project is divided into two main parts: scraping and analyzing Mars news articles, and scraping and analyzing Mars weather data.

## Project Structure
The project consists of the following components:

## Part 1: Scrape Titles and Preview Text from Mars News
In this section, the titles and preview text of Mars news articles were scraped from a specified website. The following steps were followed:

- Utilized automated browsing with Splinter to visit the Mars news site.
- Extracted relevant text elements from the website using Beautiful Soup.
- Stored the scraped data in Python data structures (list of dictionaries).
- Optionally exported the scraped data to a JSON file.

## Part 2: Scrape and Analyze Mars Weather Data
This section involved scraping and analyzing Mars weather data from a specific website. The following steps were followed:

- Used Beautiful Soup to scrape Mars weather data from the provided website.
- Assembled the scraped data into a Pandas DataFrame.
- Analyzed the data to answer various questions related to Martian weather conditions.
- Visualized the analysis results using data visualization techniques.
- Exported the DataFrame to a CSV file for further reference.

## Repository Structure
- `part_1_mars_news.ipynb`: Jupyter Notebook containing code for scraping titles and preview text from Mars news articles.
- `part_2_mars_weather.ipynb`: Jupyter Notebook containing code for scraping and analyzing Mars weather data.
- `Mars_Data.csv`: CSV file of the weather data used in the second part of the assignment.

## Tools Used
- Python
- Splinter
- Beautiful Soup
- Pandas
- Matplotlib

## Conclusion
This project demonstrates the use of web scraping and data analysis techniques to gather and analyze Mars-related data. By scraping Mars news articles and weather data, valuable insights into Mars can be obtained and analyzed. The project provides a foundation for further exploration and analysis of Mars-related data.
