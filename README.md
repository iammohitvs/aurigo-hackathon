# Daily Sales Forecasting with Temporal Fusion Transformer

## Overview

This project implements a daily sales forecasting model using the Temporal Fusion Transformer (TFT) architecture. The model leverages historical sales data along with various features such as marketing spend, weather conditions, and other relevant metrics to predict future sales.

## Features

- Data preparation for time series forecasting
- Implementation of the Temporal Fusion Transformer model
- Training and validation of the model using PyTorch Lightning
- Prediction capabilities with the trained model
- Visualization of predictions



## Usage

### Data Preparation

Prepare your data by placing your CSV file (e.g., `sample_daily_cost_dataset.csv`) in the project directory. The data should include features such as `day_of_week`, `weekend_indicator`, `holiday_indicator`, `month`, `quarter`, and various cost metrics.

### Work Flow Outline

- Running the model and uploading a 2d image, will generate a 3d model of the given construction image/blueprint.
- List of tasks, location, budget, weather will determine the priority of the ranking of the project.
- Material will be derived from the project plan and unit cost of the respective materials will be drawn.
- Based on civil component structures map volume to number of units.
- With number of units we will estimate a cost for each component.
- We will also create a forecast for the project over the upcoming months. We use past 7 days, last month and various other historical data to analyse and build our forecast.
- XG Boost regressor is used to determine number of workers based on past details.
- Safety monitoring for workers using YOLO model.
