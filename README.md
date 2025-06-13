# Pitcher Strikeout Prediction

This project predicts the number of strikeouts a pitcher might record in a specific matchup. It combines **Statcast pitch-by-pitch data**, **XGBoost modeling**, and a **Monte Carlo simulation** to generate probabilistic forecasts.

## Overview

- Scrapes detailed Statcast data for pitcher-batter matchups
- Trains an XGBoost model to estimate strikeout probabilities
- Runs a Monte Carlo simulation to project full-game strikeout outcomes
- Designed for use in predictive analytics 

## Tech Stack

- **Language:** Python
- **Libraries:** XGBoost, Pandas, NumPy, Scikit-learn, etc.
- All dependencies are listed in the notebook and can be installed via `pip` as needed

## How to Use

1. Clone the repo or download the `.ipynb` file
2. Run the notebook step-by-step in a Jupyter environment
3. Output includes model evaluation, predicted strikeout distributions, and visualizations

> No external files are needed besides an active internet connection to pull Statcast data

## Output

- Simulation results are included in the notebook
- Key output includes:
  - Expected strikeouts
  - Full probability distribution from simulation
  - Recommendations on whether to place a wager or not

## Notes

- This is a single-game simulation based on historical performance and matchup-specific tendencies
- The model does **not** currently adjust for weather, umpire, or late-breaking news

## License

This project is **not open-source licensed**. You are welcome to view and evaluate the code, but usage, reproduction, or redistribution is not permitted without explicit permission.

---

Feel free to reach out with feedback.
