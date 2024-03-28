# Predicting flight delays using Machine Learning: K-Nearest Neighbors, Naive Bayes Classifier and Random Forest algorithms.

The objective of this paper is to assist a potential airline company in enhancing their services and predicting flight delays more accurately. The primary goal is to develop a classification model capable of determining whether a flight will be delayed or not. Crucially, the focus will be on minimizing false positives, where the model incorrectly predicts a flight to be on time when it is actually delayed. 

Given that many flight delays are avoidable through meticulous planning, the successful implementation of this model has the potential to significantly improve customer experience and scheduling accuracy for our client. By accurately identifying flights at risk of delay, proactive measures can be taken to mitigate potential disruptions, thereby enhancing overall operational efficiency and customer satisfaction. Through this endeavor, our client aims to optimize their services, minimize the impact of delays, and elevate the reliability of their flight schedules.

# Data Overview
The dataset used for both training and testing models have 2201 data points with variables as 
follow:
● CRS_DEP_TIME = Scheduled Departure Time
● CARRIER = Airlines Code
● DEP_TIME = Actual Departure Time
● DEST = Airport Code of the Flight Destination
● DISTANCE = Distance of the flight
● FL_DATE = Flight Date
● FL_NUM = FLight Number
● ORIGIN = Airport Code of the Flight Origin
● Weather = Weather Code
● DAY_WEEK = Day of the Week in Number
● DAY_OF_MONTH = Date in Month
● TAIL_NUM = Tail Number of the Airlines
● Flight Status = Real Status of the Flight
● dep_delay_in_min = Delay in Minutes by Subtracting Actual Departure Time with 
Scheduled Departure Time. A positive results mean flights departed later than 
scheduled, and negative results mean flights depart earlier than scheduled
