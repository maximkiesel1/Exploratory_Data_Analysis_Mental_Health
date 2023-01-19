# Global Suicide Analysis

<img width="1179" alt="Bildschirm­foto 2023-01-15 um 19 26 47" src="https://user-images.githubusercontent.com/119667336/212559910-1874bf98-86d3-4218-abe8-9ef293a06ee5.png">

## Project Motivation

This analysis is should improve the awareness about the importantness of mental health und suicide prevention.

The goal is to get an insight in the suicide rates of the top 30 industry nations.

This helps us to understand in which direction the suicide rates were developing and 

what are areas which we need to act.



In this analysis I will look at 3 key aspects of the top 30 countries by GDP:

- Which 5 countries have the highest suicide rate over the years and how does it differ from the most recent data point?
- Which age group has highest suicide rate over the years and how does it differ from the most recent data point?
- Which generation have the highest suicide rate?

## File Descriptions

There are 3 files in this repository:
- ReadMe: General project overview
- data.csv: the dataset for the analysis
- Global_Suicide_Analysis.ipynb: the juypter notebook for this analysis


## The Analysis
For the analysis the main libraries were numpy, pandas. Viusalizations has a big part in this analyzation, 
because it´s based on principles of Descriptive Statistics. That´s why I used next to matplot plotly and pyecharts too.

Generel observations of the data were:
- Data was after the year 2015 wrong. That´s why the analyzation is just in the area between 1985 and 2015
- Some countries were underrepresented
- Low NaN-rate in the columns
- The data were based on a time series
- Suspiciously high numerical values
- Splitted data of a country 

The main findings of the analysis were:
- Almost all top 5 countries have decrease of their suicide rates. On exceptions is the Republic of Korea.
- The age group with the highest rate are people who are older the 74 years. 
- The generation with the highest suicide rate is the Silent Generation. The generation with smallest suicide rate is the Generation X.

## Summery
You can find a summery of this analysis my [blogpost]

[blogpost]: https://medium.com/@kiesel_maxim/this-analysis-of-the-top-30-countries-by-gdp-makes-you-think-about-mental-health-in-this-world-9c5e96e037bd

## Acknowledgements
The dataset for this analyzation was thankfully provided from Omkar Gowda in Kaggle:
https://www.kaggle.com/datasets/omkargowda/suicide-rates-overview-1985-to-2021
