# Disaster Response Pipeline Project

Udacity nanodegree "Data scientist", project 3 ("Recommendations for IBM Watson Studio articles")

### Summary

This project contains an analysis of user interactions with articles published on the IBM Watson Studio platform. 
After a short exploratory analysis of the data about user-article-interactions and some data cleaning, different methods are developed to make recommendations for further articles to uses (based on the dataset).

Different recommendation methods:
* Rank-based recommendations: Recommendations purely based on the overall reading statistics per article
* User-user-based collaborative filtering: Recommendations based on similarities between users (i.e. recommendation of articles which the most similiar user read)
* Matrix factorization: Recommendations based on a SVD (singular value decomposition) of the user-item matrix

### General data

Autor: Christoph Wagner
Date of publication: 31/08/2020

### File content

* Recommendations_with_IBM.ipynb : Jupyter notebook containing the implementation
* Recommendations_with_IBM.html : HTML version of the Jupyter notebook
* README.md : This readme file
* project_tests.py : Test cases for validation of project output
* Further files (top_5.p, top_10.p, top_20.p, user_item_matrix.p): Additional files for test cases included in the Jupyter notebook




