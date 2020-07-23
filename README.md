# Trends determining the success of movies

## Introduction

With new movies releasing everyday all over the World int different languages ranging from regional to global languages.Here in this project we are going to discuss the factors which determine the success of the movies.The data has been taken from the kaggle dataset and has been thouroughly studied to interpret the following results.

You may have wondered which genre does best in terms of revenue collection,movies of which genres are most produced,do movies with higher budget do better at collection or whether the duration of the movie has any affect in it's sucess.

In this project, we will examine the real information collected from the kaggle database to answer these questions and visualise the results as well by applying the data science techniques learned from the udacity data science nanodegree program.

## Data Wrangling

In this section of the report, we will load in the data,check for the problems by studying it,and then trim and clean our dataset for analysis.

### General Properties
In the beginning of the following project,we load the movie data set using the pandas module of python in the dataframe and print out a few lines in it.Then we take a look at the number of rows and columns present in the database,the number of missing values in the database.We will also study the database closely by checking the description of the dataframe such as the minimum and maximum value of each column,mean of each column,etc.

## Data Cleaning

In this part we will make the necessary changes in the database required for the analysis of data more clearly such as dropping of unneccessary columns in the database which does not add any values to our analysis,filling up of null values with the mean of the column,designing a comparison criteria to solve the question,etc.
We will start off by dropping the irrelevant data which won't help in our analysis.

## Exploratory Data Analysis

In this project we have studied the dataset and finally came to answer the questions which we started keeping in mind. During the following project we found out the following points:-

The runtime of the movies don't have any effect on the success of the movies.
The budget does not play very high role in determining the success of the movie as contrary to the popular belief we can see that movies with low budget have higher chance of being successful.
The movies with higher popularity have higher chance of being a successful movie because we can see that no flop movie has more popularity than 4.
The Adventure genre has earned the highest among all others while the documentary genre the lowest.We can see the earning for the rest of the genres through chart as well.
The Drama genre even after not being in the top 10 grossers of all time has been the most widely produced genre so far
The data provided to us is not sufficient to gather a lot of information and insights and causes us many limitations while determining several factors.A lot of rows in columns revenue,budget and runtime where filled with 0 which has to be replaced with the mean value of that column but if the actual value woukld have been present then more accurate results would have been obtained.

The popularity could not solely decide or have a say on the success of the movie because for movies with lower popularity points can be a both a hit or a flop film,but it can be clearly stated for movies with higher popularity than 4.

There were few null values in the dataset which could not have been filled with the mean values so has to be dropped because of which a loss of precision would have occurred.
