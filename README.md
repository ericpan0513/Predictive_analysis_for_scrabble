# Predictive_analysis_for_scrabble
Based on the scrabble competition on Kaggle

This project aimed to build a predictive model to predict a Scrabble player’s rating before playing the
game. Scrabble is a two-person crossword board game where players place letter tiles on the
board to create words. Players earn points based on several factors, such as the board's location
and the word's length.

The project used gameplay data from Woogles.io, an online version of Scrabble, to train and test to build
the best-performing model. The model performance was evaluated using root mean squared error
(RMSE), which captures the average difference between predicted and ground truth ratings.

**The file `Scrabble.ipynb` contains the whole script**

## Methodology ##
To build a model that minimizes the RMSE, this project adopted the following methods:
1. Feature Engineering  
Experimented with new and original features to find the features that impact prediction.
   
3. Model Comparison  
Tested five algorithms - Linear Regression, K-Nearest Neighbors (KNN), Decision Trees, Random Forest, and XGBoost - and chose the best-performing model.

## Result ##
The best model tested is `XGBoost`, with 11 features used

As the result, this project reached an RMSE = 110, which can be within top 100 leaderboard on Kaggle.


