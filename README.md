# climate_wins
This project explores how supervised machine learning can be applied to historical weather data across Europe to predict daily weather conditions and assess early signs of climate change. 

## Climate Wins Data Analysis
This repository contains Python scripts and Jupyter notebooks developed to explore how supervised machine learning can be used to predict daily weather conditions across Europe. The goal is to assess the performance of various algorithms in identifying climate patterns and provide early insight into the effects of climate change.

## Project Overview
Developed for ClimateWins, a European nonprofit, the analysis supports data-driven climate action in the face of increasing extreme weather events. As a data analyst on this project, I took on roles typically filled by a data scientist—exploring tools, optimising models, and building predictive algorithms from scratch. This analysis uses weather data spanning 1960–2022, collected from 18 European weather stations, to assess whether machine learning can accurately predict pleasant vs. unpleasant weather days, and to explore how prediction accuracy varies by geography.

## Key Questions Addressed
Can supervised machine learning accurately predict daily weather outcomes?
Do prediction accuracies differ based on region or station location?
Can ML models detect early signs of climate change, such as increased unpleasant weather trends?
Which algorithm performs best for these tasks: K-Nearest Neighbors, Decision Trees, or Artificial Neural Networks?

## Data Set Information 
- Source: [European Climate Assessment & Data Set project](https://www.ecad.eu/)
- Period Covered: 1960–2022
- Variables Included:
  - Temperature
  - Humidity
  - Precipitation
  - Snow
  - Global radiation
- Stations: 18 locations across mainland Europe
- Data Quality: Complete (no missing values)
- File Type: CSV (~16MB)
- [Download the temperature data set (.csv, 16.6MB)](https://s3.amazonaws.com/coach-courses-us/public/courses/da-spec-ml/Scripts/A1/Dataset-weather-prediction-dataset-processed.csv)
  
## Tools Used
Python – for data preprocessing, model training, and evaluation
Jupyter Notebook – for developing and presenting code/analysis
Pandas, NumPy – data wrangling and manipulation
Scikit-learn – implementing KNN, Decision Tree, and ANN models
Matplotlib, Seaborn – visualising temperature trends, predictions, and confusion matrices

## Methods & Models
- Gradient Descent – used for loss optimisation
- Supervised Learning Algorithms:
  - K-Nearest Neighbors (KNN)
  - Decision Tree Classifier
  - Artificial Neural Network (ANN)

## Evaluation Techniques:
- Confusion matrices
- Accuracy comparison across stations
- Train/test performance review

## Project Structure
- Data – raw and processed datasets
- Notebooks – individual model development and evaluation
- Visuals – graphs and images used in the presentation
- Presentation – PowerPoint summarising results

## Final Presentation
Summary of insights and recommendations presented in:

[Download PowerPoint Presentation](1.6_Presenting_Machine_Learning_Results_v3.pdf)

