# Notes

## Week 1

### Course Overview

* Week 1
    - Introduction to competitions
    - Recap
    - Feature pre-processing and feature extraction
* Week 2
    - Exploratory Data Analysis (EDA)
    - Validation
    - Data leaks (*from the leaderboards?*)
* Week 3
    - Metrics
    - Mean-encodings (categorical variables, then numeric variables and time series)
* Week 4:
    - Advanced features (statistics, distance-based features, metrics factorization, feature interactions and tSNE)
    - Hyper-parameter optimization
    - How to choose and participate in competitions
    - Technical advice (pipeline set-up, *etc*.)
    - Ensembles
* Week 5:
    - Final project
    - Winning solutions

### Project

- Local machine
- Starts at week 2 and goes all the way up to week 5

### Other assignments

Quizzes and Programming assignments

### Competition mechanics

- Data
    + CSV, text, time series, images, database dump, code, *etc*.
    + We are given the data in the competition
    + In some cases, we can use external knowledge, but check specific rules for each competition
- Model
    + Our work is to build one that outputs predictions
- Submission
    + Usually, we just submit the output, but sometimes we can be required to submit code and external sources as well
    + Some competitions allow teams
- Evaluation
    + Accuracy, Logistic loss, AUC, RMSE, MAE, *etc*.
    + It is the function that we are requested to optimize. The competition specifies which one.
- Leaderboard
    + Relative performance against all other competitors
    + The testing dataset may be divided in public and private subsets. During the competition, the leaderboard is calculated using the public dataset; the final ranking is computed based on the private dataset. This guarantees that over-fitting to the public dataset is not a good option to win the competition
    + At the end of the competition, we can choose a submission to use for the final ranking. Sometimes we can select multiple submissions, with the highest one used to compute a leaderboard position


### Competition platforms

- Kaggle
- DrivenData
- CrowdAnalytics
- CodaLab
- DataScienceChallenge.net
- Datascience.net
- other single competition sites (KDD, VizDooM, *etc*.)

### Rea-world applications *vs.* Competitions

- Data Science in the real world is complicated
    + Understand the problem
    + Formalize a task
    + Data collection
    + Data processing
    + Modelling
    + Evaluate
    + Deploy
    + Monitoring
    + Re-train on new data
    + Repeat every so often...
- In competitions, we have just:
    + Data processing
    + Modelling
    + Sometimes, it may also be necessary to:
        * Understand the problem
        * Collect data
    + In particular: we're not interested in speed, memory consumption nor in complexity analysis!

### Philosophy of competitions

- Competitions are not "all about the algorithm"
    + Insight is as (or more) important
    + *E.g.* we may even be able to solve the problem analytically
- Do no be afraid to pursue complicated solutions:
    + It is OK to use heuristics and manual data analysis
    + It is OK to produce a complex model, to use advanced pre-processing ideas and to perform huge calculations (as long as we have the computational power to do so)
- Be **creative**
