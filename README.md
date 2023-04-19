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

![image](https://user-images.githubusercontent.com/56815918/232958350-77492863-730c-4127-908e-7ebbdcfcbbda.png)


![image](https://user-images.githubusercontent.com/56815918/232958399-b80d43ed-b27a-4ba1-b972-fdadc6644d01.png)



![image](https://user-images.githubusercontent.com/56815918/232957308-58e512c9-4690-4730-b57e-c6bf43983621.png)



![image](https://user-images.githubusercontent.com/56815918/232957478-a69ffcc4-0b23-4d40-9495-fedbde0bc73c.png)


