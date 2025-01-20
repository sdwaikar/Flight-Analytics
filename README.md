# Flight Price Prediction Model ✈️

This project involves building a data pipeline and predictive model for flight prices based on historical flight data. Using advanced machine learning techniques, the model delivers accurate price predictions while uncovering key factors influencing ticket costs.

## Features

- **Data Preprocessing**: Cleaned and normalized 10,273 rows of flight data, categorized departure/arrival times, and removed outliers for robust analysis.
- **Data Visualization**: Utilized Matplotlib and Seaborn to explore relationships between airlines, total stops, and pricing through insightful plots.
- **Machine Learning Models**:
  - Linear Regression: Achieved an R² score of **73.2%**.
  - Random Forest: Improved prediction accuracy with an R² score of **78.8%**.
  - CatBoost: Delivered the best R² score of **83.5%**, highlighting key predictors such as total stops, airline type, and journey duration.

## Installation

Clone the repository:
```bash
git clone https://github.com/YourUsername/FlightPricePrediction.git
```

Navigate to the project directory:
```bash
cd FlightPricePrediction
```

Install the required libraries:
```bash
pip install -r requirements.txt
```

## Usage

1. **Data**: Place your dataset in the `data/` directory.
2. **Run Notebook**: Use Jupyter Notebook to explore and run `FlightPricePrediction.ipynb` for preprocessing, visualization, and training models.

```bash
jupyter notebook FlightPricePrediction.ipynb
```

## Dataset

The dataset contains key flight information:
- **Features**:
  - Airline
  - Source and Destination
  - Total Stops
  - Journey Duration
  - Ticket Price
- **Size**: 10,273 entries

## Results

- **Best Model**: CatBoost with R² score of **83.5%**.
- **Key Predictors**: Duration, total stops, and airline type significantly impact flight prices.

## Skills Demonstrated

- Data Preprocessing and Feature Engineering
- Data Visualization with Seaborn and Matplotlib
- Predictive Modeling with Linear Regression, Random Forest, and CatBoost
- Hyperparameter Tuning and Model Evaluation

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
