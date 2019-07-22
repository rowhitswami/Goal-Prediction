# Goal-Prediction
This repository contains solution of online hackathon 'ZS Data Science Challenge - 2019' hosted on InterviewBit.

## Problem Statement
As we all know, Cristiano Ronaldo is a legend in the football world. He has played a thousand games and scored hundreds of goals. Now, given the dataset of Cristiano Ronaldo's "attempts" on the goal target, in all his recorded and unrecorded matches, predict if he has scored a goal or not. Formally, you are given a dataset of attempts taken by Ronaldo, predict if he scored a goal or not.

## Instruction
This dataset contains the records of all the attempts Ronaldo has taken. The column "is_goal" has a missing value for all the rows we need to predict the value of "is_goal". Extract the rows with missing "is_goal" value and find the prediction as the probability [0.0 -1.0] of the goal scored.

## Algorithm Used
- LogisticRegression
- AdaBoostClassifier

## Evaluation
- Mean Absolute Error (MAE)

        Score = 1 / (1+MAE)  => 0.6798

## Leaderboard Rank (Public)
- Top 4.17%
