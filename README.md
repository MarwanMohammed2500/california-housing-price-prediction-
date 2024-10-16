# California Housing Data Analysis

This project provides an analysis of the California housing dataset, with a focus on preparing the data and applying machine learning models to predict housing prices.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Modeling Process](#modeling-process)
7. [Contributing](#contributions)

## Project Overview

This project analyzes California housing data, using various machine learning models to predict house values based on features like location, number of rooms, population, and proximity to the ocean. The main goal is to experiment with different regression models, such as linear regression, decision trees, and random forests.

## Dataset

The dataset used in this project is `housing.csv`, which contains the following features:
- `longitude`, `latitude`: Coordinates of the housing location.
- `housing_median_age`: The median age of the houses in a block.
- `total_rooms`, `total_bedrooms`: Total number of rooms and bedrooms in a block.
- `population`: Population of the block.
- `households`: Number of households in the block.
- `median_income`: Median income of households in the block.
- `median_house_value`: The target variable, representing the median house value.
- `ocean_proximity`: Distance from the ocean.

## Project Structure

The project consists of the following key sections:

1. **Dependencies**: Required libraries for data analysis and machine learning (e.g., pandas, scikit-learn).
2. **Data Loading**: The dataset is loaded and basic exploration is done (e.g., `head()`, `info()`).
3. **Data Visualization**: Visualizing the dataset before processing it to get deeper insights and a better idea of what needs to be done
4. **Data Preprocessing**: Handling missing values, feature scaling, and encoding categorical variables.
5. **Modeling**: Applying and tuning various machine learning models, including:
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
6. **Evaluation**: Model performance evaluation using metrics like RMSE and cross-validation.

## Installation

To run this project, clone the repository and install the required dependencies:

```bash
git clone <repository_url>
cd <repository_directory>
pip install -r requirements.txt
```

## Usage
1. Ensure you have the housing.csv dataset in the project directory.
2. Run the Jupyter Notebook california_housing_data.ipynb to reproduce the analysis.
``` bash
jupyter notebook california_housing_data.ipynb
```

## Modeling Process
- **Data Preprocessing**: Missing values in total_bedrooms are handled using an imputer. Categorical values in ocean_proximity are encoded using one-hot encoding.
- **Models Used**:
  - **Linear Regression**: Baseline model for predicting house values.
  - **Decision Tree**: Non-linear model capturing more complex relationships.
  - **Random Forest**: An ensemble model used for improving prediction accuracy.
- **Evaluation**: Models are evaluated using metrics such as Root Mean Squared Error (RMSE) and cross-validation scores.


## Contributions
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions.

**M.M.**
