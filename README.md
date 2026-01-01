# College Football Playoff Prediction Model

This project builds a machine learning model to predict the College Football Playoff
(CFP) game outcomes using team-level statistical differences.

## Features Used
- Points Per Game Difference (PPG_Diff)
- Points Allowed Per Game Difference (PAPG_Diff)
- Yards Per Play Difference (YAP_Diff)
- Opponent 3rd Down Conversion Difference (Opp3D_Diff)

## Model
- Logistic Regression (scikit-learn)
- Trained on simulated historical college football data
- Outputs win probabilities for Team A vs Team B matchups

## Files
- `cfb_matchup_diffs.ipynb` – feature engineering, modeling, and predictions
- `historical_cfb_random.csv` – simulated training data
- `cfb_stats.csv` – matchup input data

## Disclaimer
Historical game data was synthetically generated for demonstration purposes.
This project emphasizes modeling methodology, feature engineering,
and interpretation rather than real-world forecasting accuracy.

## Notes on Data & Tools
- Historical game data was synthetically generated for modeling practice
- Feature engineering concepts and model structure were assisted by AI tools (ChatGPT)
- All modeling logic, interpretation, and final analysis were performed by the author
