# Italian BTP Yield Curve Estimation

This project implements **Nelson-Siegel (NS)** and **Nelson-Siegel-Svensson (NSS)** models to estimate the yield curve of Italian Government Bonds (BTP).

## Features
- **Data Processing**: Loads raw Excel data of BTP prices (clean prices, coupons, maturities).
- **Financial Math**: Calculates accrued interest and builds cashflow matrices.
- **Optimization**: Calibrates NS and NSS parameters minimizing the Sum of Squared Errors (SSE) against market prices.
- **Analysis**: Performs both a single-day cross-sectional analysis and a 30-day time-series analysis.

## Structure
- `src/`: Contains the source code modules (models, plotting, data loading).
- `data/`: Input data (Excel files).
- `output/`: Generated plots and CSV results.

## Usage
1. Install requirements: `pip install -r requirements.txt`
2. Run the analysis: `python main.py`
