# Agri---Info-Crop-Management-System-
# AgriInfo: Crop Management System

## Description

AgriInfo is a comprehensive Crop Management System that provides three main functionalities:
1. Crop Recommendation
2. Crop Disease Prediction
3. Agricultural Information Analysis

This system uses machine learning models to provide insights and recommendations for farmers and agricultural professionals.

## Features

### 1. Crop Recommendation System
- Predicts the most suitable crop based on soil and climatic parameters
- Allows users to upload their own dataset for model training
- Uses a Random Forest Classifier for prediction

### 2. Crop Disease Prediction
- Identifies crop diseases from leaf images
- Utilizes a pre-trained deep learning model for image classification

### 3. Agricultural Information Analysis
- Provides insights on crop yields, cultivation costs, and production costs
- Allows users to predict crop yields based on cultivation costs
- Offers data visualizations for better understanding of agricultural trends

## Dependencies

- pandas
- numpy
- scikit-learn
- joblib
- streamlit
- tensorflow
- Pillow

## File Structure

- `app.py`: Main application file containing the Streamlit interface and core functionalities
- `crop_prediction_model.pkl`: Saved crop recommendation model
- `crop_prediction_scaler.pkl`: Saved scaler for crop recommendation
- `plant_disease_prediction_model.h5`: Saved crop disease prediction model
- `datafile.csv`: Dataset for agricultural information analysis

## Data

- Crop recommendation data should be in CSV format with columns for nitrogen, phosphorus, potassium, temperature, humidity, pH, rainfall, and label (crop name).
- Crop disease images should be in JPG, JPEG, or PNG format.
- Agricultural information data should be in CSV format with columns for crop, state, cost of cultivation, and yield information.
