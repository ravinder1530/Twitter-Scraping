# Twitter-Scraping
Python code for twitter scraping using streamlit

Scraping of Data's from Twitter with mongodb, streamlit using Snscrape

Overview of the Twitter Scraping:
Created GUI using Streamlit
•	Create any keyword or hashtag to be searched
•	Enter an option keyword Eg: "elon musk"
•	Select a start and end date
•	Number of tweet to be scraped
•	Scrape data using TwitterSearchScraper and TwitterHashtagScraper.

After Scraping the data from twitter:
•	Upload collections in database shown
•	Download CSV and JSON
•	Database collection uploaded to MongoDB
•	Displayed all tweets

LIBRARIES AND PACKAGES TO BE INSTALLED AND IMPORTED:
•	Snscrape: import snscrape.modules.twitter as sntwitter
•	Pandas: import pandas as pd
•	Pymongo: import Pymongo
•	Datetime: import Datetime
•	Streamlit: import streamlit as st

Roadmap How it works:
•	I collected keyword, start date, end date, number of tweets from the user using Streamlit
•	The above lines used for scraping data using TwitterSearchScraper and TwitterHashtagscraper.
•	Created a dataframe to store entire scraped data
•	now download the scrape data in the form of JSON and CSV
•	A new collection will be created and data is uploaded into that collection.
