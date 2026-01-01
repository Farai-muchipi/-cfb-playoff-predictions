# College Football Playoff Prediction Model

This project builds a machine learning model to predict CFP game outcomes
using team-level statistical differences.

## Features Used
- Points Per Game Difference (PPG_Diff)
- Points Allowed Per Game Difference (PAPG_Diff)
- Yards Per Play Difference (YAP_Diff)
- Opponent 3rd Down Conversion Difference (Opp3D_Diff)

## Model
- Logistic Regression
- Trained on simulated historical CFB data
- Outputs win probabilities for Team A vs Team B

## Files
- `cfb_matchup_diffs.ipynb` – feature engineering, modeling, predictions
- `historical_cfb_random.csv` – simulated training data
- `cfb_stats.csv` – matchup input data

## Disclaimer
Historical data were simulated for demonstration purposes.
This project focuses onthe  modeling approach and feature design.
