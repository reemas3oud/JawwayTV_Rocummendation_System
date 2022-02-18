# JawwayTV Rocummendation System

![alt text](https://campaign.jawwy.tv/telco-marketing-page/static//images/jawwy-logo.svg)

Recommender systems are among the most popular applications of data science today. They are used to predict “best next action” for a customer or “rating of preference” that a user would give to items. here I build a content based recommendation engine

## 1. The Dataset
The dataset is basically a collection extracted from  <a href="https://lab.stc.com.sa/dataset/en/" target="_blank">JawwyTV</a> content puplished by STC. The IPTV dataset contains the following features and it has more than 70 million rows and the size of data is more than 1 terabyte (TB), the data are:
*  User ID
* SESSION START (DATE/TIME)
* SESSION DURATION
* PROGRAM NAME
* PROGRAM DESCRIPTION
* PREOGRAM GENRE
* PROGRAM CLASS
* SERIES TITLE
* SERIES NAME
* Episode title
* Episode number


## 2. Data cleaning
* I Removed all null values using fillna

## 3. Method 
* For each of these users, we extract their whatching history using there unique ID.
* Build word2vec Embeddings for Program name
* Visualize word2vec Embeddings
* Recommending Programes to the usesrs based on similarity of program descrepston and program names


