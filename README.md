
# Stock Price Prediction Project

Welcome to the Stock Price Prediction Project. This project focuses on predicting the closing price of Microsoft (MSFT) stock using historical data and machine learning techniques.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Dependencies](#dependencies)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)


## Overview

### Problem Statement

The main goal of this project is to develop an accurate stock price prediction model for Microsoft (MSFT) based on historical stock data. Specifically, we aim to predict the closing price of MSFT stock.

### Design Thinking Process

1. **Data Collection**: We obtained the dataset from Kaggle, which contains historical MSFT stock data.

2. **Data Preprocessing**: We handled missing values, converted date data, and selected relevant columns.

3. **Feature Engineering**: We calculated moving averages, Relative Strength Index (RSI), and Moving Average Convergence Divergence (MACD).

4. **Model Selection**: We chose the Random Forest Regressor for stock price prediction.

5. **Model Training**: We split the data into training and testing sets and trained the model.

## Getting Started

### Dependencies

Before running the code, make sure you have the following dependencies installed:

- Python (>= 3.6)
- Jupyter Notebook (for running the provided Jupyter Notebook)
- Required Python packages (install using `pip install`):
  - pandas
  - numpy
  - matplotlib
  - scikit-learn

### Installation

1. Clone this repository to your local machine using `git clone` or download the ZIP file and extract it.

2. Ensure you have Python (>= 3.6) installed. You can download Python from [Python's official website](https://www.python.org/downloads/).

3. Install the required Python packages using pip:

   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```

## Usage

1. Open the Jupyter Notebook: `Stock_Price_Prediction.ipynb`.

2. Follow the code in the notebook step-by-step to execute the project.

3. You can run each cell of the notebook by selecting it and pressing Shift + Enter (or using the "Run" button).

4. The notebook provides comments and explanations for each step.

## Project Structure

The project structure is organized as follows:

- `Stock_Price_Prediction.ipynb`: Jupyter Notebook containing the code and explanations.
- `MSFT.csv`: The dataset used for the project.

## Contributing

Contributions are welcome! If you have suggestions, bug reports, or feature requests, please create an issue in the repository or open a pull request.

