# Home Credit Default Risk Analysis

This repository contains analysis and modeling for the Home Credit Default Risk competition on Kaggle.

## Project Structure

- **data-preparation-notebook.ipynb** - Exploratory Data Analysis and data preprocessing
- **modeling-notebook.ipynb** - Model training, evaluation, and feature importance analysis

## Setup Instructions

To rerun this analysis, you need to download the following datasets from the [Home Credit Default Risk competition](https://www.kaggle.com/competitions/home-credit-default-risk/overview):

**Required files:**
- application_train.csv
- application_test.csv  
- bureau.csv
- previous_application.csv
- installments_payments.csv

Run the notebooks in this sequence:

1. **First:** Run `data-preparation-notebook.ipynb`

2. **Second:** Run `modeling-notebook.ipynb`

## Future Plans

- Deploy the trained model via FastAPI
- Create a prediction API endpoint
