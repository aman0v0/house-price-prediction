# House Price Prediction

## Overview
This project utilizes **XGBoost Regression** to predict house prices based on the **California Housing Dataset**. It explores data visualization, correlation analysis, and model performance evaluation.

## Features
- **Data Loading**: Uses `sklearn.datasets` to fetch the California Housing dataset.
- **Data Preprocessing**: Converts data into a Pandas DataFrame and explores correlations.
- **Exploratory Data Analysis (EDA)**: Generates heatmaps and statistics for deeper insights.
- **Machine Learning Model**: Implements `XGBRegressor` for house price prediction.
- **Performance Metrics**: Evaluates model accuracy using R-squared and Mean Absolute Error (MAE).

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR_USERNAME/house-price-prediction.git
   cd house-price-prediction
   ```
2. Install required dependencies:
   ```sh
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost
   ```
3. Run the script:
   ```sh
   python house_price_prediction.py
   ```

## Output Example
```
R squared error:  0.83
Absolute error:  0.31
```
- Displays a scatter plot comparing actual vs. predicted house prices.

## Contributing
Feel free to contribute by improving the model, optimizing parameters, or adding new features. Fork the repository and submit a pull request.

## License
This project is licensed under the **MIT License**.

## Author
Developed by **Mohammed Aman**.

