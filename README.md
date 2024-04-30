# NoSQL Challenge


## Purpose

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

## setup database
To start this mini project I first imported my python libraries I used. Pymonog, pandas and pprint. Next I imported a new restaurant into the Database. Then I deleted all restaurants in Dover because the reviewers didn't want them as part of the analysis. After this I converted a few of the database fields to the correct data type. 

## analysis 
I first looked at establishments that had a hygiene score of 20, there was 41 establishments with a hygiene score of 20. Next I looked at restaurants in London with a rating of 4 or higher. I found that there are 33 establishments that fit this criteria in the database. Following this I looked at the top 5 restaurants that were close to the restaurant that was added to the database in the previous step. The first establishment on this list of 5 was 'Howe and Co Fish and Chips - Van 17' in Greenwich. For the final part of the analysis I looked at how many places in each local authority had a hygiene score of 0. The local authority of Thanet had the highest amount with a count of 1130. There were quite a few of local authorities with only 1 establishment Broxbourne and Kensington and Chelsea were a few of them. 
