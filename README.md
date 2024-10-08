# Restaurant Rating analysis
## Table of Content
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [References](#references)

### Project Overview
This data analysis project aims to draw out meaningful insight that would aid business entrepreneurs and investors in making informed decisions.

![dashboard image](/Screenshot_17-8-2024_105023_.jpeg)

### Data Source
Restaurant rating data: This dataset is made of 6 CSV formated files, with the information about Restaurants in Mexico, thier cuisines and information about their consumers and their preferences.
- Consumer_Preferences.csv
- Consumer.csv
- rating.csv
- Restaurants.csv
- Restaurant_Cuisines.csv
- Data_Dictionary.csv

### Tools
- PowerBI - Power Query
- Excel

### Data Cleaning and Preparation
- loading and inspection
- handling missing values
- Data cleaning and formating

### Exploratory Data Analysis
1. What's the general performance of these Restaurant
2. How these Restaurant are rated by consumers
3. What's the investment outlook

### Data Analysis
PowerBI DAX code
```
    Average overall Rating = CALCULATE(AVERAGE(rating[overall Rating]))
```
### Results and Findings
- Service rating has the least rating compared to food and overall rating
- The best selling cuisine is Mexican
- Students are the highest consumers in these restaurants compared to other occupations

### Recommendations
- Cuisines offered should be around a range that Medium Budget Consumers can meet
- Restaurant should be easily Accessible especially for consumers that take Public Transport

### References
[Data Analysis: Restaurant Ratings](https://medium.com/@tanzilo/data-analysis-restaurant-ratings-4add21602d91)
