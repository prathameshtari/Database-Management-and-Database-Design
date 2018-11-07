Football Matches and Players Database Design in SQL and NoSQL  
We are making a relational database and non relational database and also scraping data from social media sites like Facebook and Twitter to tag data

Prerequisites
Need to install python library Tweepy
Tweepy is open-sourced, hosted on GitHub and enables Python to communicate with Twitter platform and use its API.

Tweepy can be installed by running following command in the prompt.
pip install tweepy

Will need to get Consumer Key, Consumer Secret, Access Token and Access Secret can be obtained from https://developer.twitter.com/

Need to install facebook api for scraping data from Facebook

pip install facebook

You can get Facebook Accesss Token from their developer's website https://developers.facebook.com/docs/facebook-login/access-tokens

File Description
Twitter_Final_DB_Notebook_SQL : Contains code for data scraped from twitter using twitter api and sql queries generated on it
Facebook_Final_DB_Notebook_SQL : Contains code for data scraped from facebook using facebook api and sql queries generated on it
data_convert : Contains code used to convert relational database into non relational database to import it later in mongoDB
NOSQL_FACEBOOK_FINAL : Contains code used to create database in nosql and queries run on facebook on nosql database
NOSQL_TWITTER_FINAL : Contains code used to create database in nosql and quries run on twitter data on nosql database
Portfolio_Final_Project_SQL : Has technical explanation and database design explanation to create relational database using twitter and facebook api in SQL
Portfolio_Final_Project_NoSQL : Has technical explanation and database design explanation to create non relational database using twitter and facebook api in mongoDB
database : The original database from kaggle website
database_final : The database containing tagged data scraped from Twitter and Facebook
Authors
Prathamesh Tari   001886537     tari.p@husky.neu.edu
Akshay Shinde     001251097    shinde.ak@husky.neu.edu

LICENSE
MIT License

Copyright (c) 2018 Prathamesh Tari and Akshay Shinde

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Creative Commons License
This work is licensed under a Creative Commons Attribution 4.0 International License.
