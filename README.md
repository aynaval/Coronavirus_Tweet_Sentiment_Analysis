# Coronavirus Tweet Sentiment Analysis

#### -- Project Status: Completed

## Project Intro/Objective
The purpose of this project is do sentiment analysis on corona virus tweets for year 2020.

### Methods Used
* NLP
* Machine Learning
* Data Visualization

### Technologies
* Python

## Project Description
Corona tweet sentiment dataset was provided. It has 6 columns and 41157 rows. Target column is 'Sentiment' which is a categorical column. The task is to do sentiment analysis on the dataset. ScreenName and UserName were unique identifiers hence they were dropped. Location column had 20.87% Null values and most values were either special characters or gibberish, hence the column has been dropped. TweetAT column has day,month and year values of each tweet. Most tweets are from march followed by april, for all other months nly tweets from 4th of the each month are provided. Sentiment column which is the target column, has 5 unique values namely Extremely positive, Positive, neutral,Extremely negative and negative values , making it a supervised multi class classification problem. Binary classification has also been done by considering Extremely positive ,Positive and Neutral as 1 and Extremely negative and negative as 0. 

Text preprocessing is done on the OriginalTweet column, the following steps are done in text preprocessing:

1. Removing user handles
2. Removing URLs
3. Removing numbers
4. Removing special characters
5. Removing multiple white spaces
6. Removing stop word
7. Removing short words
8. Tokenization
9. Stemming
10. Vectorization

It can be concluded that for the given multiclass classification CatboostClassifier is the best algorithm and for binary classification SGDclassifier is the best algorithm.


## Needs of this project

- data exploration
- data processing/cleaning
- dealing with textual data
- multiclass classification
- sentiment analysis

### Libraries used
-numpy
-pandas
-sklearn
-matplotlib
-seaborn
-nltk
-neattext
