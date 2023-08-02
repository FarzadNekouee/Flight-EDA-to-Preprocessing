
# Flight Data Exploration and Preprocessing

## Overview
This repository contains a project that dives deep into a flight dataset to explore, understand, and preprocess the data for future machine learning tasks. We cover a wide range of techniques, from Exploratory Data Analysis (EDA) to various preprocessing methods, preparing the dataset for subsequent modeling.

## Problem
The project seeks to unravel the intricate details of flight data. The dataset encapsulates rich information about flight schedules, delays, airlines, and more. We aim to uncover patterns and insights that could be instrumental in predicting flight delays.

## Objectives
The objectives of the project are as follows:

1. __Data Understanding__: Familiarize ourselves with the dataset and its features.
2. __Exploratory Data Analysis (EDA)__: Unveil patterns, trends, and relationships between different features.
  - Univariate Analysis
  - Bivariate Analysis
  - Multivariate Analysis
3. __Data Preprocessing__: Prepare the data for future machine learning tasks.
  - Missing Value Treatment
  - Outlier Treatment
  - Encoding Categorical Features
  - Feature Scaling
  - Transforming Skewed Features

## Dataset
The flight dataset includes information about flights, their schedules, delays, and other relevant details. The features of the dataset are as follows:

- __id__: A unique identifier assigned to each flight record.
- __year__: The year the flight took place (all from 2013).
- __month__: The month the flight took place (1 to 12).
- __day__: The day of the month the flight took place (1 to 31).
- __dep_time__: The actual departure time of the flight (24-hour format).
- __sched_dep_time__: The locally scheduled departure time of the flight (24-hour format).
- __dep_delay__: The delay in flight departure (in minutes).
- __arr_time__: The actual arrival time of the flight (24-hour format).
- __sched_arr_time__: The locally scheduled arrival time of the flight (24-hour format).
- __arr_delay__: The delay in flight arrival (in minutes).
- __carrier__: A two-letter code representing the airline carrier.
- __flight__: The designated number of the flight.
- __tailnum__: A unique identifier associated with the aircraft used for the flight.
- __origin__: A three-letter code signifying the airport from which the flight departed.
- __dest__: A three-letter code representing the airport at which the flight arrived.
- __air_time__: The duration of the flight (in minutes).
- __distance__: The total distance (in miles) between the origin and destination airports.
- __hour__: The hour component of the scheduled departure time.
- __minute__: The minute component of the scheduled departure time.
- __time_hour__: The scheduled departure time of the flight (formatted as "yyyy-mm-dd hh:mm:ss").
- __name__: The full name of the airline carrier.

You can find the flight dataset here.

## File Descriptions
- `flight_data_exploration_and_preprocessing.ipynb`: Jupyter notebook containing all the data exploration, visualization, and preprocessing code.
- `flights.csv`: CSV file containing the flight data.
- `README.md`: This file, providing an overview of the project.

## How to Run
- Clone this repository.
- Open the `flight_data_exploration_and_preprocessing.ipynb` notebook in Jupyter.
- Run all cells in the notebook.

Please note that you will have to replace <link to your dataset> with the actual link to your dataset.
