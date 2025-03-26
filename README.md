
#Player Performance Prediction for Pro Kabaddi Season 11 Using Bayesian Probability


Project Overview
This project is focused on predicting player performance for Pro Kabaddi League Season 11 using Bayesian probability models. 
We aim to forecast key performance metrics such as raid points, tackle points, and overall player impact for key players. 
By utilizing a Bayesian approach, we continuously update our predictions based on prior performance data and newly observed data from ongoing matches, 
allowing for dynamic and adaptive performance forecasts.

Key Players:
The predictions are built around key players such as:
Pawan Sehrawat
Mohammadreza Shadloui Chiyaneh
Maninder Singh




Problem Statement
In sports like kabaddi, player performance varies due to numerous factors such as form, opponent strength, and even match conditions (home/away).
Static predictions fail to capture this dynamism. Bayesian models, however, allow us to update the probability of a player’s performance 
based on historical data and incoming match data, giving us a real-time understanding of how a player is likely to perform in upcoming matches.

Goals
Predict individual player performance (raid points, tackles, etc.) for each match during Season 11.
Incorporate prior season data and update predictions based on new game data after every match.
Use dynamic Bayesian models to continuously refine and improve player predictions as more data is gathered.
Provide performance insights and visualizations to guide strategic decisions such as team composition and match strategy.
Approach


1. Data Collection
Historical performance data from past Pro Kabaddi seasons for each player.
Real-time game data from Season 11 (e.g., raid points, tackle points, match outcomes).
Additional contextual data (e.g., player injuries, home/away games, opposition strength).
2. Bayesian Model Setup
Prior Distribution: Based on historical performance data for each player (average points, variance).
Likelihood Function: The probability of observing new data (game performance) given the prior knowledge.
Posterior Distribution: Updated player performance predictions after incorporating new game data.
After each match, the posterior becomes the new prior for future predictions, enabling continuous learning and adaptation.
3. Prediction Metrics
Raid Points: Number of successful raids a player is expected to perform.
Tackle Points: Number of successful tackles a defender is expected to make.
Overall Player Impact: A composite score that accounts for both offensive and defensive contributions.
4. Evaluation Metrics
Mean Squared Error (MSE): To measure the accuracy of the predicted versus actual points.
Log-Likelihood: To assess how well the Bayesian model fits the real-time performance data.
5. Visualization and Reporting
Performance Prediction Dashboards: Real-time dashboards displaying predictions for each player.
Player Performance Updates: After each match, predictions will be updated and visualized.
Player Ranking: A dynamic leaderboard of players based on their predicted performance.


