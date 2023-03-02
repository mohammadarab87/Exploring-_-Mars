# Mars Web Scraping and Data Analysis

## Background:

i will work on a full web-scraping and data analysis project.
I will extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.
I will also scrape various types of information.These include HTML tables and recurring elements.

## Project Details:

This new assignment consists of two technical products. i will submit the following deliverables:

***Deliverable 1: Scrape Titles and Preview Text from Mars News Articles***

**1-** Use automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape.

**2-** Create a Beautiful Soup object and use it to extract text elements from the website.

**3-** Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
*  Store each title-and-preview pair in a Python dictionary and give each dictionary two keys: title and preview.
*  Store all the dictionaries in a Python list.

***Deliverable 2: Scrape and Analyze Mars Weather Data***

**1-** Use automated browsing to visit the ***Mars Temperature Data Site.***
Inspect the page to identify which elements to scrape.the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html

**2-** Create a Beautiful Soup object and use it to scrape the data in the HTML table.

**3-** Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website

Here’s an explanation of the column headings:

**id:** the identification number of a single transmission from the Curiosity rover

**terrestrial_date:** the date on Earth

**sol:** the number of elapsed sols (Martian days) since Curiosity landed on Mars

**ls:** the solar longitude

**month:** the Martian month

**min_temp:** the minimum temperature, in Celsius, of a single Martian day (sol)

**pressure:** The atmospheric pressure at Curiosity's location

**4-** Examine the data types that are currently associated with each column.
If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

**5-** Analyze your dataset by using Pandas functions to answer the following questions:

* How many months exist on Mars?
* How many Martian (and not Earth) days worth of data exist in the scraped dataset?
* What are the coldest and the warmest months on Mars (at the location of Curiosity)?
* Which months have the lowest and the highest atmospheric pressure on Mars?

**6-** Export the DataFrame to a CSV file

***Files:***
* part_1_mars_news
* part_2_mars_weather


