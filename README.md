# Model Planning Notes
## Resources
https://towardsdatascience.com/predict-nba-games-make-money-machine-learning-project-b222b33f70a3 is helpful
## Modeling Over/Under point totals
  - Try Neural Network and Recurrent Neural Network
  - Output is a classification between don't bet, bet Over, and bet Under
  - Define don't bet as point total being within 3 (or some adjustable variable) of the booker's point total
    - This is special as the model is essentially seeking out when the booker's models are wildly incorrect and betting on those, rather than flat out predicting.
