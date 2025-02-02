# SMUBIA-Datathon

## Introduction
In today’s world, information is ubiquitous and knowledge omnipresent, both authentic and ingenuine articles are equally widespread on the internet. Manipulating said articles, and presenting them to the User with some pre-complete classification would greatly help the user in studying such articles, understanding the respective information. 

## Purpose
The purpose of our project is to grant Users greater control over the content they wish to see. For a User searching for different perspectives on cases, we present a simple yet effective solution - Users will get to choose articles based on reliability and its general outlook (positive/negative). This provides Users greater variety and options when it comes to parsing data sources for news.

## Features
We have incorporated several techniques into our Natural Language Processing model. The most notable features, that directly impact the User would be:
### Reliability check
Based on the URL of the article, the user will be flagged. This will be performed by scanning the URL - the prefix (www), main body (site name) and postfix (domain name).
### Common Topic
Should there be country names present in the Entity list, they will be used as a common topic for the text, otherwise, Latent Dirichlet Allocation (LDA) will be performed on the entire text to obtain a common topic. These summary words will then be used to help the User find relevant articles faster.
### Sentiment Analysis	
There will also be Sentiment Analysis performed on the textual data to understand its outlook - whether it has negative or positive connotations. This will be helpful for the User when choosing articles to work with.
