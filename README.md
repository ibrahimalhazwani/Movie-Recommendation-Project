# Movie-Recommendation

This is the code I wrote for the project course of Programming for Data Analytics.  
The project consisted in a Kaggle competion where I had to predict and recommend a list of top 10 movies for a set of users in the test set (test users).  
The original un-splitted dataset includes almost 700'000 ratings for 5690 users and 1824 items (with visual, tag, and genre features) and a subset of about 1992 users has been selected as test users. 
I had to chose which recommender algorithm to use, and after reading paper about recommended system, I deciced to use the Turicreate library with the cosine algorithm.

MAP@10 (i.e., Mean Average Precision) was used for evaluation.  

At the end I got the ... position with a score of 0.07024.
