# Exploratory data analysis for digital marketing with Seaborn

## What is EDA, and why is it important?

Exploratory Data Analysis (EDA) is usually the first step when you have data in hand and want to analyze it. In EDA, there is no hypothesis and no model. 
You are finding patterns and truth from the data. EDA is crucial for data science projects because it can: 
1. Help you gain intuition about the data.
2. Make comparisons between distributions.
3. Check if the data is on the scale you expect.
4. Find out where data is missing or if there are outliers.
5. Summarize data, calculate the mean, min, max, and variance.
The basic tools of EDA are plots, graphs, and summary statistics.

## Why Seaborn?
Seaborn is a library for making statistical graphics in Python. It builds up on top of matplotlib and integrates closely with pandas data structures. It is the equivalent of ggplot2 as of R for Python.

## About the data
In the article, we are going to use Seaborn to do EDA on a simulated digital marketing data. It is the first exercise from the book Doing Data Science by Dr. Rachel Schutt and Dr. Cathy O’Neil.
Each CSV file in the dds_ch2_nyt folder represents one day’s worth of ads shown and clicks recorded on the New York Times home page in May 2012. 
Each row represents a single user. There are five columns: age, gender(0=female, 1=male), number of impressions, number of clicks and logged-in.

## What did we interpret from the data?
* 91.3% of users reading New York Times don’t click on ads at all.
* Users younger than 18 years old are the target audience of the ad companies who promote ads in New York Times magazine. They consist of 34% of all users, and 50% of all clicked users. They are also the group that responses to the ads the most. However, the ads are not shown dissimilarly to different age groups. One advice is to promote more ads that fit young females’ tastes in New York Times.
* The 7.7 % of users with a click-through rate between 10% and 20% are those whom ad companies need to pay more attention to. 49% of them are under 18 years old, 70% are females, and 56.8% tend to sign in to New York Times.
* The recommended impression frequency is between 5 to 10 for achieving a higher click-through rate.
