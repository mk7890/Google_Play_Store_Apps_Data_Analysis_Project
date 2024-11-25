# Google Play Store Apps Data Analysis Capstone Project 
# Data analysis of google play store apps
# Presented by Moses Mugambi 

# Abstract
The Google Play Store is a vast marketplace with tens of thousands of apps catering to diverse audiences. This project focuses on analyzing Google Play Store data to uncover key insights about factores that affect app performance, user preferences, and market demand.

# Objectives
Explore how pricing affects app performance
Explore how app genres(category) influence performance
Understand app ratings and their impact on downloads.
Analyze user review sentiments and it impact on app rating
Explore relationship between app rating and number of installations

# Tools and Techniques
Loading the dataset from kaggle
Data Cleaning: Handle missing or inconsistent data.
Visualization: Use charts and graphs for insights.
Exploratory Data Analysis (EDA): Identify correlations, and patterns.

# Data Cleaning: Handle missing or inconsistent data

After loading the data from kaggle, and importing pertinent libraries,  data cleaning was performed.       

 We are analyzing two datasets:

Apps Data: Includes details such as:
Key Columns:  App name, Category, Rating, Reviews, Size, Installs, Type,  Price,        Content Rating, Genres, Last Updated, Current Version, Android Version.

User Reviews Data: Provides user feedback with sentiment analysis (positive, neutral, negative).
Key Columns: App name, Translated Review, Sentiment, Sentiment Polarity, Sentiment Subjectivity.

Mode was used to fill in missing values for Android version,  Type, and Content rating because these columns contained categorical data.
Current version column was dropped since it would not be used in this analysis.

# Data Visualization and Analysis

Relevant Charts were plotted to try to explore the objectives of the project.
Useful insights and conclusions were drawn from the analysis of the charts.
