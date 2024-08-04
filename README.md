# Hotel-Reputation-Enhancement-Through-Sentiment-Analysis-of-Google-Reviews
This project enhances a local hotel's online reputation through text classification and sentiment analysis of Google reviews. Using SerpAPI for web scraping, it performs thematic analysis of low-rated reviews and develops a predictive model to correlate guest expenditures with review sentiments. This was acheived as part of a group project with 4 other individuals.

## Business Problem
The Galmont Hotel is a luxurious 4-Star hotel in the heart of Galway. It is frequented by people from all over the world who visit Galway as it is very close to the train and bus station. For tourists, Google Search is the go-to platform to look at reviews and deciding which hotel to stay at. Therefore, it is imperative to have a good presence on their platform to attract travellers to their hotel. Galmont hotel has a review of 4 stars, which seems good, but the other 4 star hotels have a much better review which has caused a loss of revenue to the hotel. Therefore, they want to know what the guests are talking about them on Google reviews. We are a team of business analysts called The Alpha-Analyzers. Galmont Hotel has hired us to analyse the reviews that are left on Google reviews by the guests, so that they can increase their revenue and elevate the satisfaction that the guests are feeling towards the hotel. Therefore, we have performed the following analysis using the reviews from Google Search.

## Tasks performed

To achieve the objective given to us by Galmont Hotel management team, we have performed the following **Text Classification** tasks:

1. **Web Scraping:** We have used the Serp API to scrape the guest reviews that are present on the Google website.
2. **Graphical Analysis:** There were some reviews which were present in different languages, so we have used these reviews for descriptive analysis.
3. **Thematic Analysis:** After getting the reviews data, we have used the reviews which have a rating of 3 star and lower to perform thematic analysis on the data.
4. **Modelling based on spending patterns:** We have designed a classification model based on the expenditure done by the guests as analysed from the reviews.

## Web Scraping
This Python code uses the SerpApi to fetch Google Maps reviews for a specific place, identified by a data_id (Google Maps Place ID). We tried many APIs to find the one that best suited our needs.

## Graphical Analysis
### Techniques used: Data Visualization, Descriptive Statistics
We conducted a graphical analysis of the reviews data, including reviews in different languages, to perform a descriptive analysis.

## Thematic Analysis
### Techniques Used: Text Preprocessing, Natural Language Processing (NLP), Theme Identification
After obtaining the reviews data, we focused on reviews with a rating of 3 stars or lower. Here is the process for thematic analysis:

1. Data Cleaning
2. Text Preprocessing
3. Identifying Key Themes

## Modeling Based on Spending Patterns
### Techniques Used: Machine Learning, Feature Engineering, Model Evaluation
We developed a classification model to predict guest expenditure patterns based on their review sentiments. Here are the steps:

1. Data Preprocessing
2. Feature Engineering
3. Model Training and Evaluation

## Results
Our analysis provided valuable insights into the factors affecting guest satisfaction and spending patterns at the Galmont Hotel. The thematic analysis and predictive model allowed the hotel to target specific areas for improvement, thereby enhancing guest experiences and potentially increasing revenue.
