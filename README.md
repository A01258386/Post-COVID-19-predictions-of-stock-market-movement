# Post-COVID-19-predictions-of-stock-market-movement
Goal is to predict Stock segment trends based off of current Covid-19 sentiment

There are three code files in this document:

Covid.ipynb

Stocks.ipynb

Twarc.ipynb

Any of the supplemental charts used are in the Charts folder

## Libraries to install

Install the libraries using pip install <library_name> 

Pandas, pandas_datareader, yfinance, tensorflow, keras, matplotlib, numpy, twarc, seaborn, nltk, TextBlob

## Usage of Covid code

Just put the corona_tweets_1_476.csv file in wherever directory you are executing the code from. You can download a day wise file on https://ieee-dataport.org/open-access/coronavirus-covid-19-tweets-dataset#files You need to log in first, take any file and run if your goal is to execute for a specific day.  

## Usage of Stock Code

Just execute the file through a jupyter library, and make sure you have installed all libraries. Can be used to create different stock indexes, and run a LSTM on your chosen stock. Default is MSFT.

## Usage of Twarc code

Once twarc is installed, ready to start writing script for hydrating a list of tweet IDs. Before getting started with the script configure twarc with personal Twitter API keys is required. For this, on Twitter’s Developer portal, create a new application, and get CONSUMER_KEY, CONSUMER_SECRET, ACCESS_TOKEN, ACCESS_TOKEN_SECRET of the newly created application.
