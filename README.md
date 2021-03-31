# Analyze NYSE Data

Why this Project? This project will introduce you to the data analysis process that you will be using throughout the rest of the Nanodegree program. In this project, you will go through the process of calculating summary statistics, drawing an inference from the statistics, calculating business metrics and using models to forecast future growth prospects for the companies. The goal is for you to perform an analysis and also create visual tools to communicate the results in informative ways.

We have provided a clean data set for this project. Although in real life scenarios, data sets often need to be cleaned and processed before analysis can proceed. This project allows you to see what a clean data set should look like.

Background: We used the Fundamentals.csv and Securities.csv files provided by Kaggle. The Fundamentals file provides the fundamental financial data gathered from SEC 10K annual filings from 448 companies listed on the S&P 500 index. The Securities file provided the industry or sector information the companies are categorized under on the S&P 500 index.

## Understanding the Data
### Cleaning Up The Data

Although you do not need to follow these for setting up the dataset, these are some suggestions:

Change all the column names to have no spaces, but still be informative. This isn't necessary, but just a recommendation. Depending on what you do with the data in the future having spaces or special characters in the column names may not work nicely. You will see this in the next content on SQL. The following information is included in the Project data NYSE file:

* Ticker symbol: Stock symbol
* Years: Number of years for which data is provided
* Period ending
* Total revenue
* Cost of goods sold
* Sales, General and Administrative expenses
* Research and Development expenses
* Other Operating expense items
* Global Industry Classification Standard (GICS) Sector: Industry sector the company is categorized under (e.g., American Airlines with the ticker symbol AAL is categorized under Industrials.)
* GICS Sub Industry: Sub-industry sector the company is categorized under (e.g., AAL is further categorized under the sub-category of Airlines industry.)
Here is the link to the Business Metrics lesson in case you would like to review the material on the line items within the Income Statement.

### How I prepared:
I had to answer some quizzes first.

Given a dataset of NYSE I used pivot tables, to create and isolate certain parts of the data.

Like getting the mean of total revenues each year.

I used named ranges to reduce the dragging.

Created a Statistics Table and Shape Table to answer questions regarding the Data.

