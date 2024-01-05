Here is an outline for a Jupyter notebook sentiment analysis project on news headlines:

# News Headline Sentiment Analysis

## Data Acquisition

- Use the News API to gather recent headlines from various news sources

- Focus on top headlines from major outlets like BBC, CNN, NYTimes etc. 

- Store the headlines and source info as pandas dataframe

## Data Cleaning

- Remove punctuation and special characters

- Make text lowercase

- Remove stop words

- Lemmatize text

## Sentiment Analysis 

- Use TextBlob library to analyze each headline

- Calculate polarity and subjectivity scores

- Label headlines as positive, negative or neutral based on polarity threshold

