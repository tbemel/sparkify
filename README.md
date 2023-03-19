# sparkify
Udacity DataScience Nano Degree - Sparkify Project

## Project Overview
This workbook was developped in the context of my Udacity Data Science Nano Degree final project "Sparkify". 
It aims at leveraging key learned Data Science skills and the powerful capabilities of Python & Spark to load, explore, cleanse and prepare the large "Sparkiy" song event dataset to engineer and tune a machine learning model to predict customer churn. 

The Sparkify dataset is anchored in the music streaming services similar to Spotify. Customers use their mobile devices or computer to browse a music libary, listen to music. They need first to register to the service, then they can either use the 'free' service tier with advertising, no offline mode and restricted use or later upgrade and subscribe to the full experience with a monthly fee. The company aims to maximise their revenue by increasing their subscriptions and also minimizing the customer "churn", when they cancel their account. To minimize the churn, the company would like to develop a machine learning model to predict when a customer would be likely to downgrade or cancel their registration and trigger incentivizing marketing tactics to prevent the churn.

The data consists of events recorded when the user login, register, jump to different songs, upgrade, downgrade or cancel their registration.

## Problem Statement & Solutioning Strategy
The problem to be solved is to train, test and tune a machine learning model to predict the customer at risks of 'churn' i.e. downgrading/cancelling their subscriptions so marketing strategies can optimize the subscription revenues.

We will follow this overal strategy for solving the problem & develop the expected solution:
<ol>
<li><b>LOAD AND CLEAN DATA SET:</b> Load the datafile to a Spark dataframe, analyze its schema, discover its fields, field type/content/data quality and cleanse the data. The fields will also help us to refine our strategy by identifying the high/low value fields to focus on.
</li><li><b>EDA - EXPLORATORY DATA ANALYSIS:</b> on churn and user behaviours linked to churn.
</li><li><b>FEATURE ENGINEERING</b> to transform the original cleanse data set to be ready to train and test the machine learning model
</li><li><b>MODELING & TUNING</b> by selecting the best machine learning algorithm and related parameters that maximize the model accuracy.
</li><li><b>MAKE THE MODEL USABLE</b>
</li><li><b>CONCLUSION</b> of the project and key findings
</ol>

