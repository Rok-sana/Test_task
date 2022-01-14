## In this project a Machine Learning algorithm has been developed and implemented, that helps customers to get optimal nightly rent price with respect to different parameters that affect the pricing of the houses, like city, number of rooms, location, property type, etc.

The datasetfor trainig  places in repository -  Train.csv

## Overview

#### The goals / steps of this project are the following:

##### 1.Data cleaning (i.e. handling missing data, etc)
##### 2.Data visualization
##### 3.Data preprocessing
##### 4.Feature Selection
##### 5.Implementing RandomTree and DecissionTree model 
##### 6.Tuning parameters 
##### 7.Predict the pricing using test set
##### 8.Predict the pricing for Submission dataset
##### 9.Brief explanation of each step

## Data Cleaning

Missing values were found in bathrooms, bedrooms, beds, review_scores_rating, host_response_rate and etc.
For bathrooms, bedrooms, beds, review_scores_rating  any NA values were droped.

## Model Implementation

Was used 2 models Randomtree and DessionTree (based on price plot diagram)

After tuning parameters the best result was from RandomTree model with n_estimators = 50.

## Result
Сonsequently, in modelling procces were received accuracy 66, 52 % with Mean squared error 32.9

RandomTree model was applied for Submission.csv dataset. Priced was predicted and wrote to submission_final.csv file.
