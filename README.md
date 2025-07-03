# 🌊 Sea Level Predictor

Predicting future sea levels based on historical data using linear regression.

## 📌 Project Overview

This project analyzes global average sea level data from 1880 to 2013 and uses linear regression to predict future trends up to the year 2050. The dataset comes from the **U.S. Environmental Protection Agency (EPA)**.

The goal is to visualize climate change trends and understand the rise in sea levels using statistical modeling and matplotlib visualizations.

## 📁 Files

- `epa-sea-level.csv`: The dataset from EPA.
- `sea_level_predictor.py`: The main script performing data analysis and plotting.
- `sea_level_plot.png`: Output plot with trend lines and predictions.

## 📊 Tools & Libraries

- Python
- pandas
- matplotlib
- scipy.stats (for linear regression)

## 📈 Output

The final graph includes:
- A scatter plot of historical sea level data.
- A line of best fit for all data (1880–2013).
- A second line of best fit using data from 2000 onwards.
- Projections extended through the year 2050.

![Sea Level Plot](sea_level_plot.png)

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AyushJ30/Sea-Level-Predictor.git
   cd Sea-Level-Predictor
