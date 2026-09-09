# Data-Analyzer

## Project Overview

This project demonstrates an AI-ready data analysis workflow using Python and Pandas. It combines local sales data with product information from an API, performs data cleaning and analysis, and generates summary outputs.

## Technologies Used

- Python
- Pandas
- Requests
- Matplotlib
- CSV
- JSON
- REST API
- Git
- GitHub

## Project Files

- `Hands_On_5_AI_Ready_Data_Analyzer.ipynb` - Main project notebook
- `sales_data.csv` - Sales dataset
- `products_fallback.csv` - Fallback product dataset used if the API is unavailable

## Features

- Load and inspect CSV data
- Remove duplicate records
- Clean category values
- Handle invalid quantities
- Fetch product details using an API
- Use fallback CSV data if the API fails
- Merge sales and product data
- Fill missing price values
- Calculate revenue
- Identify low-stock products
- Create category-wise summaries
- Generate a revenue chart
- Export final CSV reports

## How to Run

1. Open the project folder.
2. Install the required libraries:

```bash
pip install pandas requests matplotlib
```

3. Open `Hands_On_5_AI_Ready_Data_Analyzer.ipynb`.
4. Run the notebook cells from top to bottom.

## GitHub Submission

After completing the project:

```bash
git add .
git commit -m "Complete AI ready data analyzer project"
git push origin main
```
