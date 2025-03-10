
# Ad-Click-Prediction
# Machine-Learning-Project-Starter

##### Raw Data:
I have collected the dataset from kaggle. 

source link: https://www.kaggle.com/datasets/nehadammannagari/advertising-dataset

There is very less publicly available data set for ad click.

State of project:
Model is completly implemented with Logistic Regression.

Important Results:

precision    recall  f1-score   support

           0       0.89      0.98      0.93       103
           1       0.98      0.87      0.92        97

    accuracy                           0.93       200
   macro avg       0.93      0.92      0.92       200
weighted avg       0.93      0.93      0.92       200


### Overview of Project
#### Introduction and goals:
In this project I worked with the advertising data of a marketing agency to develop machine learning algorithms that predicts if a particular user will click on an advertisement. The click through rate of a particular user for a particular advertisement is used to predict whether the web-site viewer will be interested in a particular ad or not. 

#### Important Features:
Daily Time Spent on Site, Age, Area Income, Daily Internet Usage, Ad Topic Line, City, Male, Country, Timestamp and Clicked on Ad.

There were some interesting relations between the features in dataset which I have shown using visualization.

The target variable is 'Clicked on Ad'. This variable can have two possible outcomes: 0 or 1 where 0 refers to the case where a user didn't click the advertisement, while 1 refers to the scenario where a user clicks the advertisement.

### Exploratory Data Analysis
I came up with some interesting questions on the dataset and I tried to find answers for the same during EDA process through visualization.

#### Data Preprocessing:
Performed feature selection and normalization manually. Then splitted dataset to training and testing sets using train_test_split. 
##### Models used:
Logistic Regression is incredibly easy to implement and very efficient to train. 

(Logistic Regression implementation is best instead of Linear Regression because the target variable in the dataset is of type categorical, not continuous. So, my dataset is not suitable for linear regression.)


### Conclusion: (What I leanrt)
I found that Adding features overcome underfitting, Increasing records in data can help overcome overfitting. 
