# Predictive Modelling for COVID-19 in Public Health
This repository contains the complete code, data, and documentation for my capstone project on predictive modeling for COVID-19. The goal of this project is to leverage data science techniques to provide actionable insights for public health decision-making during the COVID-19 pandemic.

## Project Overview
Public health organizations worldwide faced unprecedented challenges during the COVID-19 pandemic. This project tackles these challenges by analyzing historical COVID-19 data to:
Predict trends in confirmed cases using time-series forecasting.
Classify countries into high- and low-risk categories based on mortality rates.
Provide interactive visualizations for data exploration and stakeholder decision-making.
The project integrates data preparation, exploratory data analysis (EDA), machine learning, and dashboard development to offer a comprehensive solution.

## Features
Data Preparation:

Cleaning raw COVID-19 datasets.
Engineering features like daily growth rate, mortality rate, and recovery rate.
Exploratory Data Analysis (EDA):

Visualizing global trends in confirmed cases, recoveries, and deaths.
Correlation analysis to uncover relationships between key metrics.
Predictive Modeling:

Time-Series Forecasting: ARIMA model to forecast 30-day case trends.
Classification: Random Forest Classifier to identify high-risk countries.
Interactive Dashboard:

Developed in Power BI to provide real-time insights into COVID-19 trends.
Includes KPI cards, line charts, geographic maps, and risk classifications.

## Technologies Used
Programming Languages: Python (for data analysis and modeling).
Libraries:
Pandas, NumPy: Data manipulation.
Matplotlib, Seaborn: Visualizations.
Scikit-learn: Machine learning.
Statsmodels: Time-series analysis.
Tools:
Power BI: Interactive dashboard creation.

## Dataset
The dataset used for this project is sourced from Kaggle’s COVID-19 Clean Complete Dataset. It contains comprehensive global COVID-19 metrics, including confirmed cases, deaths, and recoveries.

## Results
Accurate forecasting of COVID-19 case trends, aiding resource allocation and planning.
High-risk regions identified with 91% precision and 92% F1-score using Random Forest.
A user-friendly dashboard providing real-time insights into pandemic dynamics.

## Repository Contents
Predictive Modelling for COVID-19 in Public Health.py: Main Python script containing data preparation, EDA, and model development.
final_covid_data.csv: Cleaned dataset used for analysis.
README.md: Project overview and setup guide.
Dashboard Screenshots: Images of Power BI dashboard components.

## How to Use
Clone the Repository:

git clone https://github.com/your-username/predictive-modelling-covid19.git
cd predictive-modelling-covid19

Install Dependencies: Make sure you have Python installed. Then install required libraries:

pip install -r requirements.txt

Run the Code: Execute the Python script to replicate the analysis and modeling.

Explore the Dashboard: Open the Power BI .pbix file to explore the interactive visualizations.

## Contributing
Contributions are welcome! If you have suggestions or enhancements, feel free to open an issue or create a pull request.




