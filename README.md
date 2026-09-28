# IPL Win Predictor

A machine learning web application that predicts the winning probability of an IPL team during the second innings of a match.

## Live Demo

[Open the IPL Win Predictor](https://ipl-win-predictor-aryan.streamlit.app/)

## Project Overview

The application predicts the probability of winning based on the current match situation.

The model considers:

- Batting team
- Bowling team
- Match venue
- Target score
- Current score
- Runs remaining
- Balls remaining
- Wickets remaining
- Current Run Rate (CRR)
- Required Run Rate (RRR)

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Jupyter Notebook

## Machine Learning

The project uses a machine learning classification pipeline with preprocessing and a trained prediction model.

The complete trained pipeline is stored in:

`pipe.pkl`

## Model Development

The project workflow includes:

1. Data cleaning
2. Exploratory Data Analysis
3. Feature engineering
4. Train-test split
5. Model training
6. Model evaluation
7. Pipeline creation
8. Streamlit deployment

## Run Locally

Clone the repository:

```bash
git clone https://github.com/aryanpati31/ipl-win-predictor.git
cd ipl-win-predictor
