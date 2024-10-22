# Analysis of Peruvian Macroeconomic Indicators (2020-2021)
## Overview
This repository contains the implementation of a Principal Component Analysis (PCA) study of Peruvian macroeconomic indicators during the period from March 2020 to July 2021, encompassing both the political transition and health crisis periods.

## Data

### The analysis includes the following macroeconomic variables:

GDP (Constant Prices 2007)
GDP Per Capita (Constant Prices 2007)
Total Imports (FOB values in millions US$)
Total Exports (FOB values in millions US$)
Capital Outflows (Public Sector Assets) - millions US$
Capital Inflows (Public Sector Liabilities) - millions US$
Capital Outflows (Private Sector Assets) - millions US$
Capital Inflows (Private Sector Liabilities) - millions US$
Interest Rate (BCRP)
Real Multilateral Exchange Rate
Non-Financial Expenditure of Central Government (millions S/)
Metropolitan Lima Price Index (monthly var%) - CPI

## Methodology
The analysis employs Principal Component Analysis (PCA) using Python 3.7, specifically utilizing NumPy and scikit-learn libraries. The methodology follows these steps:

1. Variable standardization
2. Correlation matrix calculation
3. Eigenvalue and eigenvector computation
4. Principal component selection using Kaiser criterion
5. Principal component scores calculation
6. Factor loading interpretation

## Repository Structure
```
├── data/
│   ├── raw/                  # Original data files
│   └── processed/            # Cleaned and preprocessed data
├── src/
│   ├── preprocessing/        # Data cleaning and preparation scripts
│   ├── analysis/            # PCA implementation and analysis
│   └── visualization/       # Plotting and visualization functions
├── notebooks/               # Jupyter notebooks with analysis
├── results/                # Generated figures and tables
├── requirements.txt        # Python dependencies
└── README.md              # Repository documentation
```

## Requirements

* Python 3.7
* NumPy
* pandas
* scikit-learn
* matplotlib
* seaborn

## Usage

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run the analysis scripts in the `src` directory or explore the Jupyter notebooks
