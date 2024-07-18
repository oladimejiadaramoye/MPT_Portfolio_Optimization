# MPT Portfolio Optimization

This repository contains a notebook that demonstrates the use of Modern Portfolio Theory (MPT) for portfolio optimization. The notebook includes the necessary code to construct and optimize a portfolio of financial assets to achieve the highest return for a given level of risk.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

Modern Portfolio Theory (MPT) is a mathematical framework for assembling a portfolio of assets in such a way that the expected return is maximized for a given level of risk. This repository provides an implementation of MPT using Python and Jupyter Notebook, enabling users to perform portfolio optimization on a set of assets.

## Features

- Calculation of expected returns and covariance matrix of asset returns
- Generation of random portfolios
- Calculation of portfolio performance metrics (return, volatility, Sharpe ratio)
- Identification of the optimal portfolio with the highest Sharpe ratio
- Visualization of the Efficient Frontier

## Requirements

To run the notebook, you will need the following libraries:

- numpy
- pandas
- matplotlib
- yfinance (for fetching stock data)
- scipy

These can be installed using pip:

```bash
pip install numpy pandas matplotlib yfinance scipy
```

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/oladimejiadaramoye/MPT_Portfolio_Optimization.git
cd MPT_Portfolio_Optimization
```

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the Jupyter Notebook:

```bash
jupyter notebook MPT_Portfolio_optimization.ipynb
```

2. Follow the instructions in the notebook to load the stock data, calculate returns, and perform portfolio optimization.

The notebook includes detailed explanations and code comments to help you understand the steps involved in the portfolio optimization process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project was inspired by the principles of Modern Portfolio Theory introduced by Harry Markowitz. The implementation was guided by various online resources and tutorials on financial portfolio optimization.

