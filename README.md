# Basketball-Stat-Prediction-Analysis
Analysis of Basketball Stat Predictions

# Summary

This script was created to analyze how well accurate publicly available predictions on basketball player's stats are. Currently, the script analyzes ESPN's predictions, and Basketball-Reference's. 

# Motivation
A few weeks ahead of the draft for my fantasy basketball league, I was interested in using stats to determine which players I should draft. It would be interesting to create my own homebrew model on predicting a players stats for the next season but as they say, there is no need to reinvent the wheel. Several public predictions of player's stats for the upcoming season exist online. While I could just blindly trust that these predictions were accurate, I wondered how accurate they truly were.

# Methodology

The method was fairly simply. Using cwendt94's Fantasy API, I extracted, transformed, and loaded player's data from the previous season into the script. I also loaded in ESPN's and Basketball-References predictions for that season. Then, it was simple regression analysis to determine how accurate the predicitons were.
