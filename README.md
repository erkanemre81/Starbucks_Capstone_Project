# Starbucks_Capstone_Project
Udacity Data Science Nanodegree Capstone

This is my final project for Udacity's Data Scientist Nanodegree.

# Project Motivation
I'm using simulated data from Starbucks that shows how customers react to special offers. The goal of this project is to explore the data to see which types of Starbucks customers respond to different offers. 
Additionally, I aim to build a model that can predict if an offer will be successful based on the user and the type of offer.

# Data Sets

The data is contained in three files:

* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

Here is the schema and explanation of each variable in the files:

**portfolio.json**
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

**profile.json**
* age (int) - age of the customer 
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

**transcript.json**
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record

# Results
Here is my blog post about findings an results: https://medium.com/@emreakyuz1981/starbucks-offers-data-analysis-5bf4e506e88b
