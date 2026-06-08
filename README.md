# Steam Games Analysis

Exploratory data analysis of 85,000+ Steam games to understand what drives commercial success, player retention, and genre trends.

## Business Questions

1. What factors most strongly predict a game's commercial success?
2. Which genres retain players longest?
3. Does release timing affect review scores?
4. Is there a price sweet spot that maximizes both sales and rating?
5. Which genres are growing vs declining over the past 5 years?

## Setup

1. Download `games.json` from [Kaggle](https://www.kaggle.com/datasets/fronkongames/steam-games-dataset) and place in `data/raw/`
2. Run `notebooks/01_data_cleaning.ipynb` to generate the processed dataset

## Tools

Python · Pandas · NumPy · Matplotlib · Seaborn · Power BI

## Project Structure

- `notebooks/01_data_cleaning.ipynb` — data loading, cleaning, feature engineering
- `notebooks/02_eda_analysis.ipynb` — exploratory analysis and insights
- `data/processed/` — cleaned dataset output
- `dashboard/` — Power BI dashboard files
