# Restaurant Data Analysis and Comparative Study

This repository contains two Jupyter Notebooks that perform a comprehensive analysis of restaurant data. The analysis includes data preprocessing, visualization, and statistical comparisons, focusing on various aspects such as ratings, votes, and online delivery services. Additionally, it includes a comparative study of popular restaurant chains.

## Table of Contents
1. [Introduction]
2. [Dataset Description]
3. [Data Preprocessing]
4. [Exploratory Data Analysis]
5. [Statistical Analysis]
6. [Comparative Analysis]
7. [Conclusion]

## Introduction
The goal of this analysis is to gain insights into the restaurant data by exploring different attributes, visualizing patterns, and performing statistical comparisons. Additionally, a comparative study of popular restaurant chains is conducted to determine their relative popularity and customer satisfaction.

## Dataset Description
The dataset contains information about various restaurants, including attributes such as:
- Restaurant Name
- Aggregate Rating
- Votes
- Has Online Delivery (boolean)

## Data Preprocessing
Several preprocessing steps were performed to clean and prepare the data for analysis:
- Handling missing values.
- Converting boolean values to integers (0 for False, 1 for True).
- Normalizing and transforming data as needed for analysis.

## Exploratory Data Analysis
The exploratory data analysis (EDA) section includes various visualizations and summary statistics to understand the data better.

### Key Points:
- *Distribution of Aggregate Ratings*: Histograms were used to visualize the distribution of restaurant ratings.
- *Votes vs. Ratings*: A scatter plot was created to examine the relationship between the number of votes and aggregate ratings.
- *Online Delivery*: The percentage of restaurants offering online delivery was calculated, and the average ratings for restaurants with and without online delivery were compared.

## Statistical Analysis
The statistical analysis focused on comparing average ratings between restaurants that offer online delivery and those that do not.

### Key Findings:
- *Percentage of Restaurants Offering Online Delivery*: Approximately 25.66% of the restaurants in the dataset offer online delivery.
- *Average Ratings Comparison*: Restaurants offering online delivery have a higher average rating (3.25) compared to those without online delivery (2.47).

## Comparative Analysis
The comparative analysis section includes calculations and interpretations of the average ratings and votes for specific popular restaurant chains.

### Key Points:
- *Average Ratings Calculation*: The average ratings for "Cafe Coffee Day", "Domino's Pizza", and "Subway" were calculated.
- *Average Votes Calculation*: The average votes for "Cafe Coffee Day", "Domino's Pizza", and "Subway" were calculated.

### Findings:
- *Cafe Coffee Day*:
  - Average Rating: 29.25
  - Average Votes: 29.25
- *Domino's Pizza*:
  - Average Rating: 84.09
  - Average Votes: 84.09
- *Subway*:
  - Average Rating: 97.21
  - Average Votes: 97.21

## Conclusion
The combined analysis provides valuable insights into the restaurant dataset, highlighting the impact of online delivery on restaurant ratings and other interesting patterns. Additionally, the comparative study indicates that Subway has the highest average rating and votes among the three restaurant chains, suggesting higher popularity and customer satisfaction.