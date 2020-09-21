# Soccer Results Prediction

Soccer is the world's most popular sport.
**This contest will test whether you're among the best Machine Learning engineers in the world.**
Your challenge is to use ML & Deep Learning to build a model that can best classify the outcome of a soccer match given publicly available data.

The data provided includes details on a team's recent performance, probability of winning, match location, date, recent performance against the opposing team & other recent info. In all, there are close to 100 input variables provided.

Each soccer match's results are provided under the Outcome column in the training data. A match can either be a home_team_win (indicated with 1 in the outcome colume), a draw (indicated with 0) or a away_team_win (indicated with 2).

A leaderboard of top 10 performing models will be posted daily on the contest's chat room.
The competition will run for 14 days.
A small payout has been guaranteed & will be provided to the winner of the contest.
If you win the contest, you may be hired as a consulting once the contest has concluded. Your consultation services will be compensated at a agreed payment rate.

## Data
1. **training_data** - This contains 31600 matches & their outcomes that you will use to train your model(s).
2. **validation_data** - This contains 7900 matches & their outcomes that you will use to test/validate your model(s) performance.
3. **testing_data** - This contains 500 matches (without outcomes) that you will need to predict with your model & submit their results as a list of 0,1 & 2 as part of your submission.

## Performance Criteria
- The F1 Score (https://en.wikipedia.org/wiki/F1_score) will be used to determine your model's performance against other contestants.
- This F1 Score will be based on the predictions you make for the data in point 3 above (testing_data.csv).
For the leaderboard, F1 Scores will be rounded off to 3 decimal places.
- Should there be a tie, all of the top positioned contestants will each get the guaranteed payout.
- You may post as submissions many times as you wish.

## Programming Language
1. You are encouraged to use Python for model construction.
2. You may use any classification technique as you see fit (Deep Learning, Machine Learning)

## Submission
Your submission must contain 2 things.
1. A list of your model's predictions on the training_data.csv file. This must be posted as a comment in your submission. The list must be of the form: [0,1,2,2,0...,1,2]
2. A picture of your validation data F1 Score (calculated on 'validation_data.csv').
