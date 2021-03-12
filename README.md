# Recommendation-Engine-with-IBM-Watson

## **Table of Contents:**
1. [Project Introduction](README.md#project-introduction)
2. [File Description](README.md#file-description)
3. [Libraries used](README.md#libraries-used)
4. [Results](README.md#results)
5. [Licensing, Acknowledgements](README.md#licensing-acknowledgements)

## **Project Introduction**<br/>
  In  this project, i will analyze the interactions that users have with articles on IBM Watson Studio Platform & provide recommendations about articles they would like. Below is the example of how the user dashboard looks like displaying the articles. <br/>
![Screenshot](https://github.com/prasannakr/Recommendation-Engine-with-IBM-Watson/tree/Temp/Data/IBM_Reco.jpg) <br/>
The above dashboard suggests only new articles. I will be using recommendation system using machine learning and recommend: <br/> 
  a) articles pertinent to a specific user based on history <br/>
  b) Top articles for new users <br/>
 
 ## **File Description**<br/>
  Following are the files included:<br/>
A) Jupyter notebook which contains python code - Recommendations_with_IBM.jpynb<br/>
B) Text files (.CSV) - articles_community and user-item interactions<br/>
C) Python Scripts to test our code - project_tests.py<br/>

## **Libraries Used** <br/>
Following libraries are used in this project: <br/>
  Pandas  <br/>
  Numpy <br/>
  Seaborn <br/>
  Matplotlib <br/>
  Project_tests <br/>
  Pickle <br/>
  Progressbar <br/>
  Scikit Learn <br/>
  NLTK <br/>
  
## **Results** <br/>
  Performed Exploratory Data Analysis (EDA) to understand the data i would be working & visualizations. <br/>
Started with Rank based recommendations to find the most popular articles based on the most interactions <br/>
In order to strengthen recommendations further, built User-User based Collaborative recommendation engine so that i looked at users that are similar in terms of articles they interacted with & then recommend to other users who are similar <br/>
Using Natural Language Processing (NLP), developed Content Based Recommendations. <br/>
Finally to complete, used machine learning approach with Singular Value Decomposition (SVD) using user-item interactions, build a matrix decomposition & then predict new articles that users might be interested in.<br/>

## **Licensing, Acknowledgments** <br/>
  I would like to thank Udacity for the knowledge on Experimental design & recommendations and IBM Watson for the data so that i could apply my concepts in building a recommendation system.

