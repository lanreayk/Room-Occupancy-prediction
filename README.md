# Room-Occupancy-prediction
## Introduction
This project determines if a hotel room is vacant or occupied using room physical variables/features (historical data) such as Temperature, Humidity, CO2 and Light. The project would be useful in fraud detection, perpetrated by hotel managers/receptionists who manipulate occupied room numbers. 
## Problem Statement
The problem statement was to come up with a solution for an Hotel management to solve the problem where hotel workers manipulate number of empty rooms to make cheap financial gains. I suggested that if some data suchas the ones given above are avaialble it might be possible to know if a room was actually empty or occupied at a particular time.
## Skills demonstrated
Problem solving skill, Feature engineering, Machine learning skill, Python, Sklearn, EDA, ETL
## Data Source
The data was given as an intern project during my internship at Prognoz.ai to determine my problem sloving skill as a machine learnig engineer. 
## Modelling
A logisitc regression was used been a binary classification problem. collinearity and recursive feature elimination were used as feature engineering technique and dimensionality reduction. For every manipulation the models were tested for performance comparison. The data was not balanced and its better to interprete the F1 score and Recall.
## Conclusion
The model without date and unnormalized performed better at 99% F1 score, the normalized model and the model generated after RFE (removed the column humidity ratio as it contribute less to the model) revealed the same F1 score of 93% despite removal of one feature. The model performed worst when date feature was added at 44%.
