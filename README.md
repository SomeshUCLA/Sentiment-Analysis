# Sentiment Analysis

Somesh Srivastava

Sep 12th, 2018

## Summary

This is my code for R based implementation for a kaggle project for Prediction of Stock Market movements  using 8 years daily news headlines.

The objective is to find if news headlines on a particular days has any prediction power over Stock Market Movement.

Using sentiment mapping models are fitted based on logit and elastic net method. Using ROC curve and also regressing predicted values against true values models have been tested for accuracy.  



## Data Source

1. News data: top 25 headlines historical news headlines from Reddit WorldNews Channel (Date: 8/8/2008 to 7/1/2016) (Source:Kaggle)

2. Stock data: Dow Jones Industrial Average (DJIA). (Source: Kaggle)<br>
  "1" when DJIA Adj Close value rose or stayed as the same;<br>
  "0" when DJIA Adj Close value decreased.<br>
  
 DJIA_Headline_News.csv file<br>
 columns: Date, Label (DJIA movements binary 1/0), Top 25 news (one column for each)


## R Package Requirements

* data.table
* tm
* glmnet
* ggplot2
* pROC
* SnowballC
* dplyr
* wordcloud
* ROCR
* stargazer
* sandwich
* lmtest

## Jupiter Notebook R Files

The implementation of the project was done in the following Jupyter Notebooks:

* Sentiment Analysis.ipynb


## Acknowledgments

* Prof. Lochstoer for illustrative lecture and guidance

