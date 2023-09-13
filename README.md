# Swiggy-Food-Delivery-Analysis
Swiggy Analysis (Bangalore) based on Data Scrapped from the website.



# Introduction
Data in today's time is relevant because the more data is acquired, the more analysis can be done on it. That is why companies engage themselves in data collection at each step. Such data can be in large amounts and is not easily manageable, to manage that data companies requires data scientists. Such a large amount of data is called "Big Data". And the person who analyses the data is Data Analyst. This project focuses on extracting data from the Swiggy website, performing data cleaning and preprocessing, exploring the data for insights, and visualizing the findings. The goal is to gain valuable information that can aid in business decision-making related to food delivery and restaurants on Swiggy.

## Libraries Used
- Python
- Requests
- BeautifulSoup
- Selenium
- html_to_json
- Pandas
- Numpy
- Excel

## Data Extraction Process
Swiggy uses a dynamic website, which poses challenges for data extraction. To overcome this, we employed Python libraries such as BeautifulSoup, Selenium. Here's a brief overview of the process:

1. Using BeautifulSoup and Selenium, we extracted data from the Swiggy website into HTML format.
2. The "html_to_json" library was used to convert the HTML data into JSON format, facilitating compatibility with Python.
3. We created two data frames: one for restaurants and another for food delivery.
4. Data cleaning was performed to remove duplicates and address null values.
5. The cleaned data was converted to Excel file format for further analysis.

## Data Cleaning
### Importing Data
We imported the extracted data into Excel for data cleaning and preprocessing.

### Data Cleaning Process
1. Duplicates were identified and removed.
2. Null values were handled using appropriate methods.

## Data Exploration
### Overview
Data exploration is crucial for uncovering insights and patterns.

### Insights and Findings
- We discovered [mention a few key findings].
- [Describe any trends or patterns observed].

### Data Visualization
We visualized our findings using various charts and graphs, including bar charts, pie charts, and scatter plots. Here are some examples:
![image](https://github.com/bhardwaj-priya7/Swiggy-Food-Delivery-Analysis/assets/138392873/d7f1f395-7bf3-41d5-af4d-e04c70887a1b)
![image](https://github.com/bhardwaj-priya7/Swiggy-Food-Delivery-Analysis/assets/138392873/b62f4da7-0f52-4187-b6a4-f9b9f7b12c67)



## Conclusion
### Problem Solving
This project aimed to enhance decision-making processes by extracting, cleaning, and analyzing Swiggy data.

### Key Findings
#### Key Findings
- We discovered that there is a high demand for good quality food in Bangalore, with a significant gap in the market.
- The average delivery time for restaurants in Bangalore city is shorter in hig-rated retaurants, presenting an opportunity to optimize delivery routes.
- Customer reviews and ratings are strongly correlated with restaurant order volumes, indicating the importance of maintaining a positive online reputation.

- **Location Suggestion for Remote Kitchens**
- Our analysis also identified Vivek Nagar as an underserved market for South Indian on th basis of high number of customer reviews and low ratings.
- Opening remote kitchens in Vivek Nagar could tap into this unmet demand, potentially leading to increased order volumes and revenue.

- ![image](https://github.com/bhardwaj-priya7/Swiggy-Food-Delivery-Analysis/assets/138392873/70b043d2-0abf-48bc-9f18-afe9c168ed0e)


#### How These Findings Inform Business Decisions
- The high demand for south indian, north indian and bakery suggests that partnering with restaurants that specialize in this cuisine can be a strategic move for Swiggy in Bangalore.
- Recognizing the significance of online reputation, Swiggy can work with restaurants to improve their online presence and address customer concerns promptly, ultimately boosting order volumes and customer satisfaction.

These key findings offer valuable insights that can guide Swiggy's business strategies and enhance its competitive advantage in the food delivery market.


### Limitations and Challenges
- [Discuss any limitations or challenges faced during the project].
- [Explain how these limitations may affect the project's scope].

### Limitations and Challenges
- During the data extraction process, we encountered challenges related to Swiggy's dynamic website structure. This dynamic nature made it necessary to use libraries like Selenium, which added complexity to the extraction process.

- The extraction process was also time-consuming due to the need to scroll down the page to load more data. This led to longer execution times for data extraction, affecting the overall project timeline.

- Data cleaning and preprocessing required careful handling of null values and duplicates. Despite our best efforts, some inconsistencies in the source data might still exist.

- The scope of this project was limited to a specific city or region, and the findings may not be universally applicable to all markets where Swiggy operates.

### Impact on Project Scope
- The challenges faced during data extraction and cleaning may have limited the volume of data we were able to process, potentially affecting the comprehensiveness of our insights.

- The time-consuming nature of data extraction impacted the project timeline, which could have allowed for more extensive data exploration and analysis with additional time and resources.

- While we made efforts to ensure data accuracy, the presence of inconsistencies in the source data might influence the precision of our findings.

- The regional focus of the project means that the insights and location suggestions are specific to the chosen city or region and may not apply to other markets where Swiggy operates. Further analysis would be needed for broader applicability.


## Acknowledgments
We would like to express our gratitude to the following individuals and resources for their valuable contributions to this project:

- The open-source community for developing and maintaining the Python libraries and tools that made this project possible.
- Team members for their efforts and support throughout the project.
- Youtube that provided insights and solutions to challenges faced during the project.

Your assistance and support have been instrumental in the success of this data extraction and analysis endeavor. Thank you for your valuable contributions.



