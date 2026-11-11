# DA401 Capstone Project - CJ Geier

## Project Title
Evaluating the Effect of Play-Action Passing on Defensive Disruption

## Research Question
Is play-action associated with a different defensive reaction at the snap, measured by pass rusher get-off time, and does that difference show up in pressure and offensive efficiency (EPA)?

## Data Source
NFL Big Data Bowl 2025 (Kaggle), weeks 1 to 9 of the 2022 NFL season. Files used: `plays.csv`, `player_play.csv`, `players.csv`, `games.csv`. The data is too large for GitHub, so it is stored in Google Drive. The link is in the `data/` folder.

## Methods
- Multiple linear regression (get-off time, EPA, yards)
- Logistic regression (pressure)
- Situational matching on down, distance, field position, and score
- Robust standard errors clustered by game, random effects, and EPA outlier checks

All analysis was done in R.

## How to Reproduce
1. Download the data using the Google Drive link in `data/` and place it in `big-data-bowl-data/`
2. Run `Data_exploration.Rmd`

## Google Drive
https://drive.google.com/drive/folders/1z8NQA6moHONlu6C9oL1RWN7KJV6_ReeK?usp=share_link

## Repository Structure
- `code/`: All analysis scripts or notebooks
- `writing/`: Proposal, drafts, final paper
- `figures/`: Plots, charts, visualizations
- `data/`: Link to the full dataset in Google Drive
