# FIFA World Cup 2026 — Data Analysis & Prediction

A data-driven project that predicts the FIFA World Cup 2026 winner using 
real player performance data and fixture schedules.

## Overview

This notebook analyzes two Kaggle datasets — player-level match statistics 
and the 2026 fixture schedule — to build a match prediction model from scratch 
using feature engineering and a custom scoring formula.

## What It Does

- Cleans and standardizes team names across datasets
- Aggregates player stats into team-level features:
  - Average goals, xG, player rating, defensive actions
  - Win rate, draw rate, loss rate
- Merges team stats with fixture data to create a match-level dataframe
- Engineers a FIFA ranking differential feature
- Predicts match winners using a weighted scoring model (win rate, xG, FIFA rank)
- Simulates the full knockout stage: Round of 16 → Quarter Finals → Semi Finals → Final

## Tech Stack

- Python, Pandas, NumPy
- Google Colab

## Dataset

- Player performance stats (Kaggle)
- FIFA World Cup 2026 fixture schedule (Kaggle)

## Status

🚧 In progress — knockout stage simulation complete, further analysis and 
visualizations coming.
