# 🤖 CodeAI-Tasks
<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Badge">
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas Badge">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn Badge">
</p>

A collection of projects covering Python Programming, Data Analysis, and Machine Learning tasks. This repository contains solutions for a series of assignments designed to strengthen core skills in these areas.

🐍 Task 1: Python Programming Basics
🎯 Objective
This task involves applying fundamental Python concepts to process and analyze a list of strings. It focuses on using loops, conditionals, and string manipulation to solve a series of programming problems.

⚙️ Resources
Task Notebook: CodeAi-TechAi-Task1.ipynb

Reference: Python Full Course for Beginners

📊 Task 2: Exploratory Data Analysis (EDA) of IPL Data
🎯 Objective
The goal is to analyze a ball-by-ball dataset of IPL deliveries to uncover meaningful patterns and strategic insights about players and teams.

🛠️ Core Requirements
Data Preparation: Clean and prepare the dataset for analysis.

Insight Generation: Identify top performers, key matchups, and performance trends (e.g., in powerplay or death overs).

Visualization: Present at least three actionable insights backed by visualizations.

⭐ Brownie Points
Interactive Visualizations: Use a library like Plotly to create interactive charts.

Enhanced Visuals: Develop insightful and interactive visualizations that go beyond basic plots.

📝 Submission
The solution is a single, well-commented Jupyter Notebook pushed to this repository.

📁 Resources
Dataset: deliveries_updated_mens_ipl_upto_2024

Reference:

Learn Exploratory Data Analysis (EDA) from Scratch | EDA in 5 hours | Satyajit Pattnaik

Complete Exploratory Data Analysis And Feature Engineering In 3 Hours | Krish Naik

🤖 Task 3: Machine Learning - Predicting Daily Bike Share Demand
🎯 Objective
Build a machine learning model to accurately predict the total number of daily bike rentals. This is a classic regression problem using historical data to forecast future demand.

📖 Dataset Overview: Bike Sharing Daily Data
This dataset contains daily records of a bike-sharing system with various features that influence rental demand. The goal is to predict the cnt column, which represents the total number of rentals for a given day.

Key Features:

dteday: The date of the record.

season: The season (1: spring, 2: summer, 3: fall, 4: winter).

yr: The year (0: 2011, 1: 2012).

mnth: The month (1 to 12).

holiday: Whether the day is a holiday (1) or not (0).

weekday: The day of the week (0-6).

workingday: Whether the day is a workday (1) or a weekend/holiday (0).

weathersit: The weather situation (1: Clear, 2: Mist/Cloudy, 3: Light Snow/Rain, 4: Heavy Rain/Snow).

temp: Normalized temperature in Celsius.

hum: Normalized humidity.

windspeed: Normalized wind speed.

casual & registered: Counts of casual and registered users.

cnt (Target Variable): The total count of rental bikes.

📋 Your Tasks
Data Preprocessing:

Load, inspect, and clean the dataset.

Perform feature engineering, considering how to represent categorical and date-based features effectively.

Model Building:

Build and train a regression model (e.g., Linear Regression, Decision Tree, Random Forest).

Clearly document your model choices and any hyperparameter tuning.

Model Evaluation:

Rigorously evaluate your models using appropriate regression metrics (MAE, MSE, R-squared).

Use techniques like cross-validation to ensure robust evaluation.

Conclusion:

Compare model performance and recommend the best model.

Explain the most important features for predicting bike rental demand.

⭐ Brownie Points
Instead of predicting cnt directly, build two separate models to predict casual and registered users. Your final prediction for cnt will be the sum of these two model outputs, demonstrating a deeper understanding of the data.

