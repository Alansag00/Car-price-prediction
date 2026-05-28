# Car Price Prediction using Machine Learning 🚗

## Overview
This project predicts the selling price of used cars using **Machine Learning (Linear Regression)**. It analyzes factors such as car age, fuel type, kilometers driven, transmission type, and ownership details to estimate car prices accurately.

## Features
- Data preprocessing and cleaning
- Handling missing values
- Label Encoding for categorical data
- Data visualization using graphs
- Linear Regression model for prediction
- Model performance evaluation

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
The dataset contains car-related details such as:
- Car Name
- Year
- Selling Price
- Present Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission
- Owner

## Project Structure
```

car-price-prediction/
│
├── car_price_prediction.py
├── car data.csv
├── README.md
└── graphs/
├── actual_vs_predicted.png
└── correlation_heatmap.png

````

## Installation
1. Clone the repository:
```bash
git clone <your-repository-link>
````

2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the project:

```bash
python car_price_prediction.py
```

## Model Used

This project uses **Linear Regression** to predict car prices based on historical car data.

## Evaluation Metrics

The model performance is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

## Visualizations

### 1. Actual vs Predicted Car Prices

A scatter plot comparing actual car prices with predicted values.

### 2. Correlation Heatmap

A heatmap showing relationships between dataset features.

## Future Improvements

* Try advanced models like Random Forest and XGBoost
* Improve prediction accuracy
* Build a web app for price prediction

## Author
Alansag

