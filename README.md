# Spinny Used Car Price Prediction

This project is focused on scraping data from the Spinny website for used cars and building a machine learning model to predict car prices based on various features.

## Project Overview

The primary objective of this project is to scrape used car listings from the Spinny website for multiple cities, clean the data, and then create a model to predict the price of used cars based on attributes such as make, model, year, mileage, and more.

## Features

- **Scraping Data:** The script scrapes data from the Spinny API for used cars in different cities.
- **Data Cleaning:** It processes the scraped data to ensure it’s structured for analysis and modeling.
- **Modeling:** A machine learning model (such as regression) is built to predict car prices based on the features.
- **Visualization:** Data visualization techniques are used to explore the relationships between different features and the car prices.

## Requirements

- Python 3.10
- Libraries:
  - pandas
  - requests
  - json
  - scikit-learn
  - matplotlib
  - tqdm

You can install the required libraries using pip:

```bash
pip install pandas requests scikit-learn matplotlib tqdm
