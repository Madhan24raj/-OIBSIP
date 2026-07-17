# Retail Sales Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset containing 1,000 transactions. It identifies customer purchasing patterns, product-category performance, monthly sales trends, and actionable business insights.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

## Project Structure

```text
├── Images/                         # Charts generated during analysis
├── Output/
│   └── cleaned_retail_sales.csv    # Cleaned dataset
├── Retail_EDA.ipynb                # Main analysis notebook
├── retail_sales_dataset.csv        # Original dataset
└── requirements.txt                # Python dependencies
```

## Key Insights

- The dataset contains 1,000 transactions with no missing values or duplicate records.
- Electronics generated the highest total revenue.
- May was the highest-sales month; September had the lowest sales.
- Female customers generated slightly more revenue than male customers.
- Customers aged 46–55 contributed the highest revenue.
- Price per Unit has a strong positive relationship with Total Amount.

## How to Run

1. Install the required libraries:

```bash
pip install -r requirements.txt
```

2. Open `Retail_EDA.ipynb` in VS Code or Jupyter Notebook.
3. Select a Python kernel.
4. Click **Run All** to run the complete analysis.

## Author

Madhanraj Ganeshan