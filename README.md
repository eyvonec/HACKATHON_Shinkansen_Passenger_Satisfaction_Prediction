# HACKATHON_Shinkansen_Passenger_Satisfaction_Prediction
This repository contains the code I used to rank No. 1 in terms of accuracy (0.9569687) to predict the Shinkansen Passenger Satisfaction during the Hackathon as part of the optional event for the MIT Professional Education: Applied Data Science Program: Leveraging AI for Effective Decision-Making.


## Shinkansen Bullet Train Passenger Experience Prediction

This problem statement revolves around understanding passengers' experiences on the Shinkansen Bullet Train in Japan and determining the factors that contribute to their overall satisfaction using machine learning techniques.

### Objective

The main objective of this machine learning exercise is to analyze the relative importance of various parameters in influencing passengers' feedback regarding their travel experience on the Shinkansen Bullet Train. The goal is to predict whether a passenger was satisfied or not based on their overall experience.

### Dataset

The dataset consists of two separate sets:

1. **Travel Data:** Contains information related to passengers and attributes associated with the Shinkansen train they traveled on. This data is provided with the file named `Traveldata_train.csv`.

2. **Survey Data:** Represents aggregated data from surveys indicating passengers' post-service experience. This includes feedback on various parameters related to travel. The survey data is provided with the file labeled `Surveydata_train.csv`.

### Data Description

- **Target Variable:** `Overall_Experience` (1 represents 'satisfied', and 0 represents 'not satisfied')

### Dataset Split

Both the train and test datasets are provided separately.

- **Train Data:** Used for building machine learning models. It includes labels for the target column (`Overall_Experience`).
- **Test Data:** Used to evaluate the performance of the trained model on unseen data.

### Submission Format

A CSV file containing predictions for each participant's `Overall_Experience`. The submission file should have exactly 35,602 entries plus a header row with the following columns:

- **ID**
- **Overall_Experience** (contains 0 & 1 values, where 1 represents 'Satisfied' and 0 represents 'Not Satisfied')

### Evaluation Criteria

The model's performance was evaluated based on the accuracy score, which is the percentage of correct predictions made by the model. The accuracy score is calculated as the total number of correct predictions (True Positives + True Negatives) divided by the total number of observations in the dataset. The best possible accuracy is 100% (or 1), and the worst possible accuracy is 0%.
