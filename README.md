# Relation-Between-Elite-and-Non-Elite-User-Reviews-and-Business-Rating-Classification-on-Yelp-Data
For this project, publicly available Yelp dataset is used which is present on their website. First a detailed exploratory analysis of data is carried out and then the project tries to
analyze the relationship between reviews given by elite users and the reviews given by normal users. This analysis is based on sentiments of reviews posted by elite users
and normal users. The relationship between them is checked by building a linear regression model. The sentiments are calculated by using nrc lexicons which categorizes words
in 10 different emotional categories like anger, anticipation etc.

Project not only analyzes the relationship between elite and normal user reviews but also tries to build classification models that are able to predict star rating of a
business based on the sentiments calculated from reviews of all users. For achieving this we are building different models like K-Nearest Neighbor, SVM and C5.0.

*Research Questions:*

1) Do reviews given by elite users have any impact on reviews given by normal users?
2) Which model among KNN, SVM and C5.0 can classify star rating of businesses and achieve better
   results?
   

## CODE ##
 
 ### R code : 
 
 1. Code1_JSON_to_CSV.R - Input files is in JSON format which are converted into CSV.(structured) 
 2. Code2_Script.R - Data Manupulation. 
 3. Code7_Exploratory_Analysis.R - Data exploration. 
 4. Code3_Sentiment_Elite.R - Openion mining of Elite users.
 5. Code4_Sentiment_nonelite.R - Openion mining o Non-Elite users.
 6. Code5_lm.R ,Code6_adm_yelp.R - model building, classification and predictive analysis.
