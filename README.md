# Zomato-Order-Analysis

## Overview

This notebook analyzes zomato data, focusing on ratings, cost, and other attributes, using Python for exploratory data analysis (EDA).

## Dataset

The dataset, **"Zomato order data .csv"**, includes:
- `name`: Restaurant name
- `online_order`, `book_table`: Availability details
- `rate`, `votes`: Ratings and votes
- `approx_cost(for two people)`: Approximate cost

## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

## Structure

1. **Imports**: Required libraries.
2. **Data Loading**: Loads the dataset into a DataFrame.
3. **Cleaning**: Processes ratings into numerical format.
4. **Analysis**: Displays dataset insights and visualizations.

## Key Function

### `handleRate(value)`
Converts rating strings (e.g., "4.1/5") to float values (e.g., 4.1).

## Usage

1. Place the dataset in the same directory as the notebook.
2. Open and run the notebook:

```bash
jupyter notebook Analysis.ipynb
```

Let me know if you need any further edits!
