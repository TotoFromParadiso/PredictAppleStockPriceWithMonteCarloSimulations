# Apple Stock Price Prediction

This project uses a Monte Carlo Simulation to predict possible future prices of Apple stock using historical market data. The program analyzes past stock performance, calculates expected returns and volatility, and generates multiple future price simulations.

## Features

- Loads and processes Apple stock data from a CSV file
- Calculates daily returns, annual return (`mu`), and volatility (`sigma`)
- Runs 1000 Monte Carlo simulations
- Predicts possible stock price movements for 252 trading days
- Visualizes simulated stock price paths using Matplotlib

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib

## How It Works

1. The program loads historical Apple stock data.
2. Daily percentage returns are calculated.
3. Average annual return and volatility are estimated.
4. Monte Carlo Simulation generates random future stock prices.
5. The results are displayed in a graph.

## Installation

Clone the repository:

```bash
git clone <your-repository-link>
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib
```

## Usage

1. Place the `AAPL.csv` file in the project folder.
2. Run the Python script:

```bash
python predictapplestockprice.py
```

## Output

- Expected future stock price after 252 trading days
- Visualization of simulated stock price paths

## Example

The graph displays multiple possible future price movements for Apple stock generated through simulation.

## Project Goal

The goal of this project is to practice financial data analysis, probability simulation, and data visualization using Python.

## Author

Created by [Sandro Makhatadze]
