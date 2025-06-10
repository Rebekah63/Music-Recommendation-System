# Music-Recommendation-System
This is a group project with my team mates at Refactory Academy . We worked on a song recommendation system for local music  startups in Uganda. We borrowed the spotify data set from Kaggle .All credit goes to my group for the dedication , effort and teamwork on this project.

## Problem statement 
Many local streaming platforms face low user retention because their recommendation systems are inefficient, causing users to leave for competitors with better personalized music suggestions-impacting users’ satisfaction, the platform’s growth, and artists’ exposure.

## Project Objective
To develop a machine learning model that predicts the popularity of a song based on its musical features and recommends it to listeners based on their preferences.
The music recommendation system will use both content based and collaborative filtering .

## Project Approach 
- Use supervised machine learning models: random forest and Deep Learning to explore audio feature data, perform content based filtering and forecast whether new tracks will likely be liked by users ( Content based filtering  )
- Use unsupervised learning to cluster songs and  Leverage PCA and similarity metrics to build a song recommendation engine based on user-selected tracks. (Collaborative filtering)

## About Dataset 
Source: Spotify Dataset from Kaggle – includes 170,000+ tracks with audio features. (data up to 2020). 
This rich dataset provides a comprehensive collection of songs along with attributes such as danceability, energy, tempo, acousticness, valence, and popularity scores.
The dataset consists of 19 columns divided into 
- numerical features-like tempo, loudness, and speechiness-
- categorical features such as key, mode, artist names, and release date. 
These features form the foundation for our analysis and model development to improve music recommendation systems by better understanding what drives user engagement.

## Tools used 
1. Python ( Data manipulation , Exploratory data Analysis , Visualization)
2. Machine Learning Algorithms to make predictions ( Supervised and Unsupervised learning )
3. Microsoft Powerpoint - Presentation

##  Results & Insights
- Random Forest: 86% accuracy, 77% recall for "liked" songs.
- K-Means Clustering: 5 meaningful song groups identified via PCA.
- Business Impact: Better ad targeting, artist feedback, and user retention.

## Team & Acknowledgments
Developed by Group 7 at Refactory Academy:
1. Wendy Mbabazi 
2. Zaina Namugabo
3. Namuyanja K Rebecca
4. Mugisha Isaac
