# [Stocks_Sentiment_Analysis](https://github.com/parthshah28/Stocks_Sentiment_Analysis)

AI/ML based sentiment analysis model which can be used to understand sentiment from public tweets as a factor while making a buy/sell decision of securities.

## Dataset:
The Dataset has **5791 rows and 2 columns**.

![](https://github.com/parthshah28/Stocks_Sentiment_Analysis/blob/main/images/1.png)

## Data Cleaning:

### 1.Remove Punctuations From Text
I defined a function to remove punctuations.

![](https://github.com/parthshah28/Stocks_Sentiment_Analysis/blob/main/images/2.png)

### 2.Remove StopWords
I used **nltk** library to remove stopwords.

![](https://github.com/parthshah28/Stocks_Sentiment_Analysis/blob/main/images/3.png)

## WordCloud:
Here I have plotted WordCloud using **wordcloud** module.

![](https://github.com/parthshah28/Stocks_Sentiment_Analysis/blob/main/images/4.png)

## Visualize Cleaned Dataset:
#### The maximum number of words in any document is: 20

![](https://github.com/parthshah28/Stocks_Sentiment_Analysis/blob/main/images/5.png)

## Prepare The Data Using Tokenizing and Padding:
Tokenizer allows us to vectorize text corrups. Tokenization works by turning each text into a sequence of integers.

First split the data into test and train dataset. Training data has 5211 rows and 1 column. Testing data has 580 rows and 1 column.

Now Create a tokenizer to tokenize the words and create sequences of tokenized words and then add padding to training and testing.

Finally Convert the data to categorical 2D representation.

## Custom Based Deep Neural Network To Perform Sentiment Analysis:

![](https://github.com/parthshah28/Stocks_Sentiment_Analysis/blob/main/images/6.png)

## Confusion Matrix:

![](https://github.com/parthshah28/Stocks_Sentiment_Analysis/blob/main/images/7.png)

####  To understand in more detail go to [Stocks_Sentiment_Analysis.ipynb](https://github.com/parthshah28/Stocks_Sentiment_Analysis/blob/main/Stocks_Sentiment_Analysis.ipynb)
