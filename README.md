# Global Temperature Trend Analysis Using CO₂ Emissions

This project analyzes projected global and regional temperature trends using historical and future CO₂ emissions data. It uses the NorESM2 climate model and builds regression models to assess the impact of cumulative CO₂ on temperature rise.

## What’s Included

- Analysis of historical + projected CO₂ emissions (1850–2100)
- Linear regression model for predicting global warming
- Region- and country-level temperature modeling using climate data
- Visualization of trends, residuals, R² scores, and sensitivity by country
- Custom analysis comparing Canada and Pakistan
- Command Line Interface (CLI) to predict temperature rise from CO₂ levels

## Key Techniques

- Data cleaning and interpolation
- Regression modeling (global + country-level)
- NetCDF handling with `xarray`
- Weighted temperature averaging using latitude-based weights
- CLI for quick predictions using saved regression coefficients

## Tech Used

Python, pandas, xarray, matplotlib, scikit-learn, argparse
