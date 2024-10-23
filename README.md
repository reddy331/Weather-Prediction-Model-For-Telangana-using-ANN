# Weather Prediction Model for Telangana Using ANN

This project uses Artificial Neural Networks (ANN) to build a weather prediction model specifically for the Telangana region. It leverages meteorological data to predict key weather parameters such as temperature, humidity, and rainfall.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [File Structure](#file-structure)

## Project Overview
This project implements a machine learning model using ANN to forecast weather conditions based on historical data. The model is trained to predict various weather features including maximum and minimum temperature, humidity, precipitation, and more. The dataset used is focused on the Telangana region.

## Technologies Used
- Python
- TensorFlow/Keras (for ANN)
- Pandas and NumPy (for data preprocessing)
- Scikit-learn (for model evaluation)
- Matplotlib/Seaborn (for visualizations)
- Jupyter Notebook (for interactive analysis and training)

## Dataset
The dataset (`weather data.csv`) consists of historical weather data from the Telangana region. It includes parameters such as:
- Maximum and Minimum Temperature
- Humidity (RH2M)
- Precipitation (PRECTOTCORR)
- Atmospheric Pressure (PS)
  
The data is preprocessed to handle missing values, scale features, and prepare it for input into the neural network.

## Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/weather-prediction-telangana-ann.git
   cd weather-prediction-telangana-ann
