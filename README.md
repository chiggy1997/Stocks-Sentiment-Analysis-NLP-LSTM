# Stocks-Sentiment-Analysis-NLP-LSTM
Stocks Sentiment Analysis NLP LSTM

## 1.Overview 
### Goal	
	-Humungous data on social media about a stock which is impossible to go through and make decisions.
	-Leverage technology to gain interesting insights and make better investment decisions.

### Impact	
	-Based on the signals of the model investors can make confident and well informed decisions.
	-Time saved by 95% by leveraging technology.
	-Avoid decision fatigue and analysis paralysis.

### Challenges Faced
	-Collection of data from twitter through twitter API.
	-Structuring and making sense of unstructured and noisy text data.
	-Data cleaning and preprocessing.
	
### Interesting findings	
	-For positive class the words : long, bullish, buy call, high, hold are very common.
	-For negative class short, bearish, buy put, low very common.
	-Both the classes have some common words like volume which can imply both sentiments and add noise in the data.
	
	
	
## 2.Code and resource used:
	-Pandas, Numpy, Matplotlib.py.	
	-Seaborn and Plotly Express.
	-Wordcloud.	
	-NLTK.

## 3.About the data:	
	


	
## 4.Data gathering:
	-IEEE dataport  + twitter.
	
## 5.Data Preprocessing:
	-Data cleaning.
	-Removing Punctuations and stopwords.
	-Stemming and Tokenization.
	
## 6.Modelling
	-Split the data into 90% train and 10% test.
	-Performed Stemming, tokenisation , encoding and embedding to reduce output dimensions
	-Built a simple custom LSTM network for Sentiment analysis with the following configuration
	-Optimizer used was ADAM 
	-Loss taken was categorical cross entropy and metrics taken as accuracy.
	
