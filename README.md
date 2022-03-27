# Airline Passenger Satisfaction
- [Content](#Content)
- [1-Reading & Analysing Data](#1-Reading-&-Analysing-Data)
 - [1.1- Null value control](#1.1--Null-value-control)
 - [1.2- Describing Parameters](#1.2--Describing-Parameters)
- [2-Visualization Data](#2-Visualization-Data)
 - [2.1-Categorical Data](#2.1-Categorical-Data)
   - [Bar Chart](#Bar-Chart)
 - [2.2-Numerical Data](#2.2-Numerical-Data)
   - [Histogram](#Histogram)
   - [Density Function](#Density-Function)
   - [Box Plot](#Box-Plot)
- [3-Preprocessing Data](#3-Preprocessing-Data)
 - [3.1-Dummies Variable](#3.1-Dummies-Variable)
 - [3.2-X_train-y_train, X_test-y_test](#3.2-X_train-y_train,-X_test-y_test)
- [4-Data Modeling](#4-Data-Modeling)
 - [4.1-Logistic Regression](#4.1-Logistic-Regression)
 - [4.2-k-Nearest Neighbors](#4.2-k-Nearest-Neighbors)
 - [4.3-Decision Tree Classifier](#4.3-Decision-Tree-Classifier)
 - [4.4-Ridge Regresion](#4.4-Ridge-Regresion)
 - [4.5-Lasso Regression](#4.5-Lasso-Regression)

## Content
This dataset contains an airline passenger satisfaction survey. 
- Gender: Gender of the passengers (Female, Male)
- Customer Type: The customer type (Loyal customer, disloyal customer)
- Age: The actual age of the passengers
- Type of Travel: Purpose of the flight of the passengers (Personal Travel, Business Travel)
- Class: Travel class in the plane of the passengers (Business, Eco, Eco Plus)
- Flight distance: The flight distance of this journey
- Inflight wifi service: Satisfaction level of the inflight wifi service (0:Not Applicable;1-5)
- Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient
- Ease of Online booking: Satisfaction level of online booking
- Gate location: Satisfaction level of Gate location
- Food and drink: Satisfaction level of Food and drink
- Online boarding: Satisfaction level of online boarding
- Seat comfort: Satisfaction level of Seat comfort
- Inflight entertainment: Satisfaction level of inflight entertainment
- On-board service: Satisfaction level of On-board service
- Leg room service: Satisfaction level of Leg room service
- Baggage handling: Satisfaction level of baggage handling
- Check-in service: Satisfaction level of Check-in service
- Inflight service: Satisfaction level of inflight service
- Cleanliness: Satisfaction level of Cleanliness
- Departure Delay in Minutes: Minutes delayed when departure
- Arrival Delay in Minutes: Minutes delayed when Arrival
- Satisfaction: Airline satisfaction level(Satisfaction, neutral or dissatisfaction)

[Data from kaggle.com](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)

## Task
- 1) What factors are highly correlated to a satisfied (or dissatisfied) passenger? [ANS-1](#ANS-1)
- 2) Can you predict passenger satisfaction? [ANS-2](#ANS-2)
