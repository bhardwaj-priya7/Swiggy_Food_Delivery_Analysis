# Swiggy-Food-Delivery-Analysis
Swiggy Analysis (Bangalore) based on Data Scrapped from the website.

# Introduction

Data in today's time is relevant because the more data is acquired, the more analysis can be done on it. That is why companies engage themselves in data collection at each step. Such data can be in large amounts and is not easily manageable, to manage that data companies requires data scientists. Such a large amount of data is called "Big Data". And the person who analyses the data is Data Analyst. One such process can be seen in this project, where we (as a team) share the code for Data Extraction from "www.swiggy.com/", from its website wherein I Extracted the data from its Bangalore Domain, and on the basis of data we did some Exploratory data analysis for valuable insights.

# Steps involved in the process:
Data Extraction using Python Libraries
Data cleaning
Data Exploring
Data Presenting
Data Analysis
Data extraction from the Swiggy website can be easily done using Python libraries like requests and Beautifulsoup like most of the websites, however, swiggy uses a dynamic website wherein it does not use web page no. for easily iterating over pages for data, instead here we have to scroll down to the end of the page to get more data. So libraries like Pyshadow and selenium come in handy at this part. Using BeautifulSoup, Selenium, and python we were able to extract the data into HTML format, then we used the library "html_to_jason" to convert the html data to Json file, which acted as a bridge between Python and html format. Then, using pandas and numpy libraries we were able to create two data frames one had data for restaurants and the other have data for food delivery, then using pandas we dropped any duplicates and checked for null values. lastly, we converted it to an Excel file format.

After creating an Excel file, we imported both of the files into power query and performed data cleaning

After data cleaning, we studied the data to find the possible insights and clues that might help for a business decision.

we did data visualisation using multiple charts by taking various insights.
