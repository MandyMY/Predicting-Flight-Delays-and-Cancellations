# Predicting-Flight-Delays-and-Cancellations
Final Project for Parallel ML Course

## Abstract

When planning a trip, passengers should keep in mind that airlines do not guarantee their schedules, delayed and cancellation of flights always break our plans. Especially, airlines are cutting 20% to 50% of their domestic flight schedules by April 1, 2020, due to the coronavirus outbreak. So predicting the flight status before traveling is very necessary for passengers to plan a trip and prepare for the worst situation.

This project is predicting flight delayed by the data provided by The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics. The predicting is based on the airline companies, origin and destination, flight time and other factors in the dataset.

Delayed time was transferred to be a categorical variable, then I built some classifiers include Logistic Regression, Random Forest, LightGBM and CatBoost to train the data, LightGBM perform best in this project. Moreover, I tried to accelerate these classifiers by adding multiple CPU or GPU and got ideal results.

Keywords: Flight Delay, Parallel, Machine Learning, GPU, Classifier
