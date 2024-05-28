# House Price Prediction Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Model and Methodology](#model-and-methodology)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Project Overview
This project aims to predict house rent prices in nine metropolitan cities in India using machine learning models. The dataset was collected from makaan.com and includes various features influencing rent prices such as location, size, and number of rooms. The objective is to build a predictive model that can provide insights into the rental market dynamics.

## Dataset
The dataset contains information about rental properties in Ahmedabad, Bangalore, Chennai, Delhi, Hyderabad, Kolkata, Mumbai, Pune, and Surat. It comprises 15,300 records with 13 features, including house type, size, location, city, coordinates, price, currency, number of bathrooms, verification date, description, security deposit, and status.

## Installation
To run this project, ensure you have Python installed. You can install the necessary packages by running:

```bash
pip install pandas numpy seaborn matplotlib missingno scikit-learn
```

## Usage

1 . Clone this repository:
```sh
git clone https://github.com/yourusername/house-price-prediction.git
```
2 . Navigate to the project directory:
```sh
cd house-price-prediction
```
3 . Run the Jupyter notebook for analysis:
```sh
jupyter notebook Group25_HRP.ipynb
```

## Model and Methodology

The project involves the following steps:

1 . **Data Collection**: Data was scraped from makaan.com.
2 . **Data Cleaning**: Handled missing values and outliers.
3 . **Exploratory Data Analysis (EDA)**: Conducted univariate and multivariate analysis to understand data distribution and relationships.
4 . **Feature Engineering**: Extracted and transformed features to improve model performance.
5 . **Model Building**: Implemented Linear Regression and Random Forest models to predict rent prices.

## Packages Required
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Missingno
- Scikit-learn (LinearRegression, train_test_split, mean_squared_error)

## Results
The models' performance was evaluated using Mean Squared Error (MSE). The results demonstrate the models' capability to predict rental prices with reasonable accuracy. Detailed results and visualizations are provided in the notebook and the report.

## Contributing
Contributions are welcome! Please create a pull request with detailed descriptions of your changes.

## License
This project is licensed under the MIT License.
