# KDrama

Reference from:
https://www.kaggle.com/chanoncharuchinda/sample-top-100-korean-dramas/notebook
https://github.com/swati-gwc/DramaList/blob/main/WebScrapingMyDramaList.py
https://medium.com/@apoorvareddy612/korean-drama-analysis-4da6146ffaab
https://github.com/doranbae/Recommender-for-Korean-Dramas
https://feifang.github.io/New-Lipstick-Effect/
https://towardsai.net/p/artificial-intelligence/an-ai-practitioners-guide-to-the-kdrama-start-up-56ab95c2afd8

DATASET

Korean Weekly Rating in Naver
https://search.naver.com/search.naver?where=nexearch&query=%EB%93%9C%EB%9D%BC%EB%A7%88

International Rating in DramaList
https://mydramalist.com/shows

Most awards won
https://haen.ai/l/dataset-of-korean-dramas-with-the-most-awards-won

https://www.reddit.com/r/datasets/comments/ioepvd/looking_for_datasets_related_to_korean_dramas_and/
https://dramaqa.snu.ac.kr/Dataset


Tnms & Nielsen ratings
http://www.koreandrama.org/voice-season-4/

How-TO:

https://www.analyticsvidhya.com/blog/2021/12/comprehensive-project-on-building-a-movie-recommender-website/
https://medium.com/analytics-vidhya/recommender-systems-in-10-minutes-2e50b430f98d


Read & Laugh:
Start Up Review by an AI engineer https://towardsai.net/p/artificial-intelligence/an-ai-practitioners-guide-to-the-kdrama-start-up-56ab95c2afd8


## Background

## Overview of Project

I love KDrama but not all of them. However, I do not have specific genres and would like to have a Recommender System to introduce me to "new" or older good KDramas.

Another link is the 100 most popular: https://mydramalist.com/shows/top_korean_dramas

### Purpose

## Analysis And Challenges

* Think of potential way to achieve Collaborative Filtering. URL/statistics have some information

## Methodology: Analytics Paradigm
https://cloudy.achakladar.com/a-movie-recommender-engine-using-k-means-and-collaborative-filtering-and-deployed-to-kubernetes-ckj7mj1280292w7s1bzxw4uiv

#### 1. Decomposing the Ask


#### 2. Identify the Datasource
While the API for mydramalist.com exists, currently no API keys are given out anymore.

Use webscraping method from: https://towardsdatascience.com/web-scraping-basics-82f8b5acd45c

https://stackoverflow.com/questions/58419896/writing-scraped-data-into-json-using-python

Inspect the website HTML that you want to crawl
Access URL of the website using code and download all the HTML contents on the page
Format the downloaded content into a readable format
Extract out useful information and save it into a structured format
For information displayed on multiple pages of the website, you may need to repeat steps 2–4 to have the complete information.

### 3. Define Strategy & Metrics
**Resource:** Python 3, Flask, Pandas, Jupyter Notebook, Splinter, Beautiful Soup, PyMongo, MongoDB, HTML5Lib, LXML

#### 4. Data Retrieval Plan

* dramalist.com: this is a good site for getting information due to the high number of users and critics therefore making the dataset viable. Also it is the only English site with this traffic.

#### 5. Assemble & Clean the Data

#### 6. Analyse for Trends

#### 7. Acknowledging Limitations

1. Actually it is better to get information directly from the Korean search engine, Naver, however it is all in Korean and currently I do not have the knowledge on how to deal with NLP or non-English information

2. The current list does not factor newly released dramas and therefore maybe a bit outdated.

3. It is most likely that older dramas have more critics and therefore the ranking will be more normalised and/or higher

4. New dramas might have fewer critics and therefore unreliable ranking

5. Classification - User-based: Not sure where to get this data for classification

6. Classification - Product / Item-based: Do not have enough users-based data

7. How to make use of user reviews in each drama for NLP machine learning?

#### 8. Making the Call:
The "Proper" Conclusion is indicated below on [Summary](#summary)

## Analysis

>June Temperature Aggregates

![June Temperature Aggregates](resources/junetempdesc.png)

>June Temperature

![June Temperature](resources/junetemp.png)

## Summary

## Appendix
