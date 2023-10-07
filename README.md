# weather-prediction

## Introduction

This repository contains code and data for a weather prediction project that utilizes historical temperature data from past several years to train a Linear Regression model. The trained model is then used to predict tomorrow's temperature based on learned features.

## Dataset

The dataset used for this project is available in the `temperature_data.csv` file. It contains the following columns:

- `prcp`: amount of precipitation.
- `tmax`: maximum temperature in a day.
- `tmin`: minimum temperature in a day.

## Model Used

**Linear Regression**: Linear regression is a simple and widely used regression model that assumes a linear relationship between the input features (in this case, historical temperature data) and the target variable (tomorrow's temperature).

## Installation

To run the code in this repository, you'll need the following libraries:

```bash
pip install numpy pandas scikit-learn
```

## Usage

1. Clone this repository:

```bash
gir clone: https://github.com/harshil-1402/weather-prediction
cd weather-prediction
```

2. Run the Jupyter Notebook or Python script to train the Linear Regression model and make predictions.

```bash
jupyter notebook weather_prediction.ipynb
# OR
python weather_prediction.py
```

3. The model will be trained on historical temperature data and make predictions for tomorrow's temperature.

## Results

After running the model, the predicted temperature for tomorrow will be displayed. Keep in mind that the accuracy of the prediction may vary based on the quality and quantity of historical data and the assumptions made by the Linear Regression model.

## Conclusion

This project demonstrates the use of Linear Regression for weather prediction based on historical temperature data. While this is a simplified example, it provides a foundation for more complex weather forecasting models that incorporate additional features such as humidity, atmospheric pressure, and wind patterns.

Feel free to explore the code and dataset further, and consider enhancing the model with additional features and more advanced machine learning techniques for more accurate weather predictions.
