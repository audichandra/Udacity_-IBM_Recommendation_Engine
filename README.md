# Disaster Response Pipeline Project

### Table of Contents 
1. [Description](https://github.com/audichandra/Udacity_IBM_Recommendation_Engine#Description)
2. [Installation](https://github.com/audichandra/Udacity_IBM_Recommendation_Engine#Installation)
3. [File Descriptions](https://github.com/audichandra/Udacity_IBM_Recommendation_Engine#File-Descriptions)
4. [Results](https://github.com/audichandra/Udacity_IBM_Recommendation_Engine#Results)
5. [Licensing, Authors, and Acknowledgements](https://github.com/audichandra/Udacity_IBM_Recommendation_Engine#Licensing)


### Description 

This project is a recommendation engine system for the IBM Watson community which we have to recommend the articles that the user will like by using the recommendation engine. The datasets contained the article community details and the list of the articles that have been read by the users (anonymized)   

There are five segments in this project: 
1. Exploratory Data Analysis
2. Rank Based Recommendations
3. User-User Based Collaborative Filtering
4. Content Based Recommendations (EXTRA - NOT REQUIRED)
5. Matrix Factorization


### Installation
This project was created and run using Python version 3.0.

Plugins and imports used were: 
1. Pandas, MatplotLib, SKlearn


### File Descriptions 
1. Data folder contained the csvs of the data
2. The HTML and notebook of this project 
3. project test python file which served as the guide for the right answers
4. top 5, 10 and 20 of the aswers of top recommendation   
5. README document


### Results 

**1. Exploratory Data Analysis**

In this section, we dive deeper into the details of the data and the exploration as well as some of the questions that we must answer in order to comple this section. 

**2. Rank Based Recommendations**

This is the first methodology of the recommendation system where we recommend the articles to the users based on the popularity of the articles. These are then the articles we might recommend to new users (or anyone depending on what we know about them). The example: the most popular article in the community

**3. User-User Based Collaborative Filtering** 

In this methodology, we recommend the articles to the users based on the another users that have read similar articles which we could also recommne the articles to anothe user with similar reading history or profile. The example: User A and User B that have read the same article which we can also recommend it to the User C that have similar reading history of User A and User B.

**4. Content Based Recommendations (EXTRA - NOT REQUIRED)** 

In this section, we can also recommend the articles to the users based on the wording of the article's content that is in common with the articles that have been read with the users by using the NLP; however, in this project, we will not cover this section.  

**5. Matrix Factorization** 

Finally, by using the user-item interaction, we can build a matrix decomposition: a matrix which we will use to see the accuracy of the prediction of the article recommendations toward the right users. We also include the recommendation in improving the recommendation system even further. 


### Licensing, Authors, and Acknowledgements

- Authors: [Audi Chandra](https://github.com/audichandra)
- License: [MIT](https://opensource.org/licenses/MIT)
- Acknowledgements 1: [Udacity](https://www.udacity.com/) and its communities in providing and supporting the completion of this project for Data Science Nanodegree 
- Acknowledgements 2: [IBM Watson](https://www.ibm.com/watson) in providing the datasets and explanation 
