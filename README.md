# Tanzanian Water Wells Classification

##Overview
Water is a basic need for humans for health and sanitation. In remote areas, water wells become the source of this requirement. For a population of over 65 million people in Tanzania, being able to service and maintain this wells  becomes paramount and therefore fulfils the sustainable development goal number 6: Clean Water and Sanitation

## Business Understanding

MWN Consultancy has been tasked to predict the condition of a well through the data provided. Through modeling, we should come up with the best model that classifies pumps into 3 categories;  functional, non-functional, requires repair.

This model should be able to categorise the current installed base but also declare combined characteristics and features of attributes that are precursors to the conditions of the wells

## Objectives

**1. Identify and present the best model that classifies the state of the well with highest accuracy**

## Data understanding
The data seems to have been split between train and test data
Merging was done to achieve a train test split

## Data Cleaning
Cleaning Training Data
Handling null values

A lot of duplicates were eliminated on column level as well as dropping null values

## Preprocessing
Encoding was done at 3 levels; label, frequency and one hot encoding depending on the number and type of variables
Scaling was done for models that were sensitive such as KNN, logistic regression and SVM

## Modeling
The following models were performed;
1. Logistic Regression
2. Gradient Boost
3. Random Forest
4. Decision Trees
5. Support Vector Machine
6. K Nearest Neighbour

## Conclusion and Recommendation
The best performing model was the tuned Random forest model with 75 % recall on class 1 which is the functonal needs repair.

Focus on this metric will help increase repairs on faulty wells by early detection.

Better tuning will increase the overall performance.

All other models had very low performance on accuracy and recall and will not be best suited for this dataset

## Limitations
Limitations experienced were; shorter timelines and some tuning models eg REF have a very long computation time and therefore affect delivery time as well as time to process other models




