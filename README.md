# HLTV Players Historical Dataset

**Author:** Zhaksylyk Abilmansur

This dataset contains 500 records of Counter-Strike player statistics and 9 columns. It is published for educational data analysis and machine learning experiments.

## Columns

| Column | Description |
|---|---|
| player | Player nickname |
| country | Player country |
| age | Player age in years |
| kills | Total kills recorded |
| deaths | Total deaths recorded |
| kd_diff | Difference between kills and deaths |
| rating | Player performance rating |
| headshot_percent | Headshot percentage |
| adr | Average damage per round |

## Data Quality

The CSV contains no missing values or fully duplicated rows. Statistics represent historical records and should not be treated as current player statistics.

## Machine Learning Task

The dataset can be used to compare Decision Tree and Random Forest classifiers.

For this educational experiment, a binary target is defined as:

- **1:** rating ≥ 1.10
- **0:** rating < 1.10

This threshold is an experimental choice, not an official player classification. The `rating` column must be excluded from input features because it directly defines the target. Player nicknames are also excluded from model training.

## Intended Use

Exploratory data analysis, classification, tree visualization, Gini impurity calculations, feature importance analysis, and model comparison.
