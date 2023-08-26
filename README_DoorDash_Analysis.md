
# DoorDash Restaurant Analysis

## Table of Contents
1. [Overview](#overview)
2. [Notebook Structure](#notebook-structure)
3. [Data Features](#data-features)
4. [Conclusion](#conclusion)
5. [Requirements](#requirements)
6. [How to Run](#how-to-run)

## Overview <a name="overview"></a>
This repository contains a Jupyter Notebook that performs an in-depth analysis of a DoorDash dataset. The analysis includes data cleaning, exploratory data analysis (EDA), and preliminary machine learning model building.

## Notebook Structure <a name="notebook-structure"></a>

### Data Loading and Initial Exploration
Load the DoorDash dataset and get an initial understanding of its structure and features.

### Data Info
Gather metadata about the dataset, such as data types, null values, and basic statistics.

### Feature Dropping and Engineering
Identify and drop irrelevant or redundant features. Engineer new features that may be useful for analysis or modeling.

### Location Name Analysis
Investigate the distribution and frequency of different location names ('loc_name').

### Unique Location Names
Find 'loc_name' entries that appear only once in the dataset, providing insights into unique restaurants.

## Data Features <a name="data-features"></a>
The dataset contains several features, including but not limited to:
- `searched_zipcode`
- `searched_city`
- `searched_state`
- `distance`
- `delivery_time`
- `review_count`
- `review_rating`

## Conclusion <a name="conclusion"></a>
The notebook serves as a comprehensive guide for understanding the DoorDash dataset, from initial data loading to in-depth analysis. It prepares the ground for future work, including more advanced analyses and machine learning model development.

## Requirements <a name="requirements"></a>
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## How to Run <a name="how-to-run"></a>
1. Clone this GitHub repository.
2. Navigate to the downloaded folder and open a terminal.
3. Run `jupyter notebook` to start the Jupyter Notebook server.
4. Open the notebook `DoorDash Analysis.ipynb` in your browser.
5. Run the notebook cells in sequence.

