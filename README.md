# Portfolio Projects

## Haptik Text classification
### [Link to Haptik Text Classification]()
Classification of Haptik user queries into appropriate Classes using NLP and ML techniques.
The goal of the project was to detect the user intent and classify the user chat into the following categories - food,recharge,support,reminders,travel,nearby,movies,casual and other.

A chat can be classified into multiple categories Ex. “Are there any offers going on?” This query could belong to all the domains in which transactions are possible ( travel, recharge, food, movies, home services, etc) Thus it was a Multiclass and multilabel problem.

Implemented a multi-label classifier using the training data. The classifier tagged all the possible domains (food, support etc) for each query using Decision Tree, Logistic Regression and Random forest algorithms.
Achieved a label accuracy of 94% and subset accuracy of 74%

## Vehicle Prediction on Highway
### [Link to the Vehicle Prediction](https://github.com/gowthamdongari/Vehicle_Prediction/blob/master/final_model.ipynb)
we are provided with a sample that represents our data which is very less to perform any operation and come up with a model
Understanding the data as how many readings are recorded if a vehicle is passing through the metal strip, Given the small sample the avg reading for each vehicle is well differentiated, So considered the 6 Sigma level approach by finding the upper and lower boundary by observing mean and standard deviation for vehicle types.
Then we calculate the -3 and +3 sigma levels and use this for predicting the accuracy, i.e 99%

To build a Machine Learning Model Creating a data resembling our sample and we build a machine learning model on it
creating the data considering the average lengths of bike (1.8m), car(4.5m), & bus-(14m) given the speed of the vehicles is 15 kmph i.e is 4.1666 m/s, we calculated the average time taken for the vehicles to cover its own length
now we create a dataset accordingly and created new Polynomonial Features and moving average to predict the vehicle Using      Random Forest Classifier.

## Predicting survival of passengers on the Titanic dataset
### [Link to the Titanic Survival project](https://github.com/gowthamdongari/Titanic_Survival)
The aim of this project was to get acquainted with the tools, learn about the different data structures (NumPy Arrays, Series and DataFrames) how they work and what they offer,and practice the key steps on the whole data analysis process.In this project I Explored the dataset containing information about Titanic passengers by using NumPy and Pandas, which are two popular Python packages used for manipulating datasets. 

I used Decision tree & Random forest algorithms to predict the percentage of passengers who survived.
I am currently at 1304th rank for the given competition on Kaggle with an accuracy score of 79.90%.

## Subreddit Recommender System for Reddit users
### [Link to Subreddit Recommender System]()
The goal of the project is to to predict possibly interesting subreddits to a user based on their comment history. The hypothesis of the recommender model is, given an ordered sequence of user subreddit interactions, patterns will emerge that favour the discovery of paticular new subreddits given that historical user interaction sequence.

Implemented the recommendor system using the SVD algorithm.
Verified the accuracy of the model by removing a subreddit from the user history and checking if the recommdation system did output the removed subreddit as a recommendation.

## Visualizing-Earnings
### [Link to Visualizing-Earnings](https://github.com/gowthamdongari/Visualising_Earnings)
The aim of the project is to get an experience on using the Tools in Python such as Pandas data Structures, Matplotlib etc..
Here the dataset contains data of different majors in college and contains information on Male and Female distribution and 
Employment stats, Median Salaries and how they are employed like Part-time or fulltime etc.. 













