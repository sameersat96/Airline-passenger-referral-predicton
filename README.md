# Airline-passenger-referral-predicton

In this project, I have built various predictive models to find whether the reviewer recommends travelling by a particular airline. The goal is to find the model that fits best into the dataset 'data_airline_reviews.xlsx'



![image](https://user-images.githubusercontent.com/95841292/179391482-33640d94-84b5-4c81-8e8f-cbf2d6eec59b.png)




## Problem Statement
Data includes airline reviews from 2006 to 2019 for popular airlines around the world with multiple choice and free text questions. Data is scraped in Spring 2019. The main objective is to predict whether passengers will refer the airline to their friends.

Feature descriptions briefly as follows:

airline: Name of the airline
overall: Overall point is given to the trip between 1 to 10.
author: Author of the trip
reviewdate: Date of the Review
customer review: Review of the customers in free text format
aircraft: Type of the aircraft
travellertype: Type of traveler (e.g. business, leisure)
cabin: Cabin at the flight
date flown: Flight date
seatcomfort: Rated between 1-5
cabin service: Rated between 1-5
foodbev: Rated between 1-5
entertainment: Rated between 1-5
groundservice: Rated between 1-5
valueformoney: Rated between 1-5
recommended: Binary, target variable


# WORKING WITH DIFFERENT MODELS

## Logistic Regression
## DecisionTree
## Random Forest
## Gradient Boosting
## XG Boost
## SVM
## Naive bayes


# Conclusion

•	Logistic Regression has the highest recall value It gave the recall of 95.12% followed by SVM which gave 94.91%.
•	Support Vector Machine has the highest accuracy from the models but others are also performed very well SVM gave 95.40% accuracy. Even after using Grid Search CV our models are giving similar accuracy.
•	‘British airways' has the maximum number of trips and this happened due to its ultra low cost fare compared to other airlines.
•	'No' responses are more as compared to 'Yes' responses in recommended that means airlines have to focus on some aspects to make there fliers happy.

