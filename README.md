# Smart Financial Analyzer

A Python-based personal finance tool that analyzes spending data and provides 
probabilistic risk assessments for future expenses.

## Features
- Categorizes transactions into Needs, Wants, Savings, and Income using keyword matching
- Computes descriptive statistics (mean, standard deviation, variance)
- Time-series analysis using derivatives and integrals to detect spending trends
- Detects unusual spending spikes using standard deviation thresholds
- Monte Carlo simulation (10,000 iterations) to forecast future spending scenarios
- Visualizations: category bar charts, time-series plots, and simulation histograms

## Requirements
pip install pandas numpy matplotlib openpyxl

## How to Use
1. Prepare an Excel file with columns: Date, Description, Amount
2. Update the file_path variable in the script to point to your Excel file
3. Run the script and enter your monthly budget when prompted
4. Four visualizations will appear sequentially — close each to proceed

## Sample Data
A sample dataset (finance_test_data.xlsx) is included for testing.

## Built With
Python, Pandas, NumPy, Matplotlib

## Authors
Steven Wenfeng Xiong, Nikolaos Karigiannis, Rishi Bhattacharyya  
