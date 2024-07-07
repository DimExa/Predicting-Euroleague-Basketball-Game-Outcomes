# Forecasting Euroleague Game Results
This repository contains two Jupyter notebooks that demonstrate the process of forecasting Euroleague basketball game results using team statistics and Elo ratings.

## Notebooks
### 1. Prepare Teams Data (01 - Prepare teams data.ipynb)
This notebook preprocesses and prepares the team statistics data for the Euroleague basketball seasons 2022-23 and 2023-24. The data includes team stats for each regular season game up to round 26 of the 2023-24 season. The data source is [Hack A Stat](https://hackastat.eu/en/home-page-eng/).

#### Key steps:
* Import and clean data for the 2022-23 and 2023-24 seasons.
* Standardize team tags.
* Calculate additional metrics such as shooting chances.
* Save the processed data for further analysis.

### 2. Forecast Game Outcomes (02 - Forecast game outcomes.ipynb)
This notebook forecasts the outcomes of Euroleague games using the processed team statistics data and Elo ratings. The Elo ratings are calculated and updated for each team after each round of games.

#### Key steps:

* Load the processed data.
* Calculate Elo ratings for each team.
* Train a Logistic Regression model and a Random Forest Classifier to predict game outcomes.
* Perform out-of-sample predictions.
* Evaluate the performanceof both models.
