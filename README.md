# Weather-Prediction-and-Learning-AdaBoost
This is an excerpt from my code for a Machine Learning and Statistical Analysis problem set (COSC 274) where I train a classifier to predict the weather and implement AdaBoost to improve prediction accuracy. The source of the meterological data was not credited in the problem set.¶

The data consists of various meterological measurements (from the Weather.csv file), including whether or not it rained the following day. The objectives of the problem set were to 1) train a classifier to accurately predict whether it will rain the following day on unseen test data where the value was withheld and 2) construct the AdaBoost algorithm from scratch, implement it with the trained classifiers, and observe how it impacts the classifier prediction accuracy

Here, I have replaced the AdaBoost algorithm I wrote from scratch with scikit learn's Adaboost function in case this problem set is used again in the future for the course (so it cannot be used).
