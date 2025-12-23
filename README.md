# Air Quality Prediction Using Neural Networks

## Overview
This project leverages Deep Learning to predict air quality parameters. A key component of this project was the construction of a unified dataset from **multiple raw sources**, enabling the model to learn from a rich and diverse set of environmental conditions.

## Features
- **Data Engineering:**
  - Aggregated data from various external sources.
  - Merged and harmonized datasets to ensure temporal alignment.
  - Automated cleaning of missing values using time-based interpolation.
- **Exploratory Data Analysis:** Visualizations of pollutant correlations and missing value heatmaps.
- **Machine Learning Models:**
  - **Neural Network:** Built with TensorFlow/Keras (Dense layers with Dropout).
  - **Linear Regression:** Used as a baseline for performance comparison.

## Technologies Used
- **Language:** Python
- **Data Manipulation:** Pandas (Merging, Joining, Cleaning), NumPy
- **Modeling:** TensorFlow, Keras, Scikit-Learn
- **Visualization:** Matplotlib, Seaborn

## Dataset
The dataset was constructed by **merging multiple sources** to include hourly/daily readings of:
- **Weather:** Temperature, Humidity, Wind Speed, Pressure.
- **Pollutants:** PM2.5, CO, NO, NO2, O3, PM10, SO2.

## Results
- Successfully integrated disparate data streams to achieve high model accuracy.
- Visualized the relationship between predicted and actual pollutant levels using scatter plots.
