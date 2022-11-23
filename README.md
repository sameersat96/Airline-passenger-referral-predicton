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


# Visualization 

# 1) class distribution 

![newplot (2)](https://user-images.githubusercontent.com/95841292/202970086-2ea18271-5535-48e4-b6d3-713d0af348f8.png)

# 2) cabin type with recommendation

![image](https://user-images.githubusercontent.com/95841292/202970171-c1ed9b97-ef91-4f62-af5b-b3ea6a33bfaa.png)


# 3) balance dataset of tgt variable

![newplot (3)](https://user-images.githubusercontent.com/95841292/202970254-e255cb34-91af-4067-9bd2-9ff40bec9039.png)

# 4) correlation 

![image](https://user-images.githubusercontent.com/95841292/202970363-ced5d751-1987-427d-b4fa-545518e83f2c.png)


# WORKING WITH DIFFERENT MODELS

# Logistic Regression
# DecisionTree
# Random Forest
# Gradient Boosting
# XG Boost
# SVM
# Naive bayes


# Conclusion

•	Logistic Regression has the highest recall value It gave the recall of 95.12% followed by SVM which gave 94.91%.
•	Support Vector Machine has the highest accuracy from the models but others are also performed very well SVM gave 95.40% accuracy. Even after using Grid Search CV our models are giving similar accuracy.
•	‘British airways' has the maximum number of trips and this happened due to its ultra low cost fare compared to other airlines.
•	'No' responses are more as compared to 'Yes' responses in recommended that means airlines have to focus on some aspects to make there fliers happy.



# 📜 Credits

Sameer Satpute | Data Scientist | Machine Learning Engineer | Deep Learning enthusiast

Special thanks to AlmaBetter

Contact me for Data Science Project Collaborations

[![image](https://user-images.githubusercontent.com/95841292/202914376-d5a83f3d-110a-4476-896e-1da078b185dc.png)](https://www.linkedin.com/in/sameersatpute/)
[![image](https://user-images.githubusercontent.com/95841292/202914715-787f6ae3-d9f6-491c-9cae-c717131ddebd.png)](https://github.com/sameersat96)
[![image](https://user-images.githubusercontent.com/95841292/202914883-bce71634-6c2b-4305-8020-4b240cb76e41.png)](https://medium.com/@sameersatpute)
![image](https://user-images.githubusercontent.com/95841292/202914940-5d5eba71-e45d-4e95-8dfe-65e45d255aec.png)




# 📚 References

1.  https://phdessay.com/airline-industry-research/
2.  Kaggle
3.  Analytics Vidya

