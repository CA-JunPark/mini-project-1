# Mini Project 1: Regression Challenge

    Jun Park
    Aristide Kanamugire

### Project Description And Motivation

The goal of this project is to build regression models that predict the median house value in California districts using demographic and geographic features. Housing price prediction is an important real-world problem because it helps support decisions in urban planning, real estate analysis, and economic studies.
This project applies to regression concepts learned in class, including data exploration, preprocessing, feature engineering, model training, and evaluation.

### Dataset Description (source, features, target)

This project uses the California Housing dataset from sklearn.datasets.

•Source: sklearn.datasets.fetch_california_housing

•Target variable: Median house value (MedHouseVal)

•Number of instances: 20,640

•Features:

    Median income
    House age
    Average number of rooms
    Average number of bedrooms
    Population
    Average household size
    Latitude
    Longitude

The dataset contains only numerical features and does not include missing values.

### Setup instructions

    git clone <this repo>
    cd mini-project-1
    python -m venv .venv
    source .venv/Scripts/activate or .venv/bin/activate
    pip install -r requirements.txt

run .ipynb files with created python environment.

### Result summary with Key Meterics

![Alt text](/src/Result_Metric.png)

### Team Member Contributions
Aristide Kanamugire: 01_data_exploration.ipynb

Jun Park: 02_modeling.ipynb

Together: Learning Hub Report
    



