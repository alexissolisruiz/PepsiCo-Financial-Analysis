# PepsiCo vs Coca-Cola Company Financial Analysis

## Overview

This repository contains financial analysis data comparing PepsiCo and The Coca-Cola Company. The analysis includes horizontal and vertical financial comparisons and ratio calculations.

## Files

- **PepsiCo Vs CocaColaCompany Financial Analysis.csv**: Contains overall financial analysis data comparing both companies.
- **PepsiCo Vs CocaColaCompany Financial Analysis (Horizontal Analysis).csv**: Contains horizontal analysis data, comparing financial performance over time.
- **PepsiCo Vs CocaColaCompany Financial Analysis (Vertical Analysis).csv**: Contains vertical analysis data, comparing financial components as percentages of a base figure.

## How to Use

1. Download the CSV files.
2. Open them in a spreadsheet program (Excel, Google Sheets) or use Python (pandas) for data analysis.
3. Analyze trends and comparisons between PepsiCo and The Coca-Cola Company.

## Dependencies (for Python users)

To analyze the data using Python, install pandas:

```sh
pip install pandas
```

Example usage:

```python
import pandas as pd

# Load data
horizontal_analysis = pd.read_csv("PepsiCo Vs CocaColaCompany Financial Analysis (Horizontal Analysis).csv")
vertical_analysis = pd.read_csv("PepsiCo Vs CocaColaCompany Financial Analysis (Vertical Analysis).csv")
overall_analysis = pd.read_csv("PepsiCo Vs CocaColaCompany Financial Analysis.csv")

# Display first few rows
print(horizontal_analysis.head())
```

## License

This project is for educational and analytical purposes. No official affiliation with PepsiCo or The Coca-Cola Company.

## Author

Alexis Solis Ruiz

