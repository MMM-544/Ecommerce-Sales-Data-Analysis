# E-Commerce Sales Data Analysis Using Python

## Project Overview
This project analyzes the Online Retail dataset to explore sales performance, identify top-selling products, examine country-level sales distribution, and understand monthly sales trends.

The project uses Python and data analysis libraries to clean, process, analyze, and visualize real-world retail transaction data.

## Project Objectives
- Analyze overall sales performance and revenue.
- Identify the top-performing products by revenue and quantity.
- Determine the countries generating the highest sales.
- Examine monthly sales trends.
- Calculate key business performance indicators.

## Dataset
- **Source:** [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Original Records:** 541,909
- **Original Features:** 8
- **Analysis Period:** December 2010 – December 2011.

## Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning and Preparation
The dataset was prepared through the following steps:
- Removed duplicate records.
- Excluded cancelled invoices.
- Removed records with negative unit prices.
- Handled missing product descriptions.
- Retained missing customer IDs for general sales analysis.
- Created a new Sales column by multiplying Quantity by UnitPrice.

## Key Findings
- **Total Revenue:** £10,642,110.80
- **Total Quantity Sold:** 5,645,017 units
- **Total Invoices:** 22,062
- **Number of Countries:** 38
- **Number of Product Descriptions:** 4,208
- **Top Country by Sales:** United Kingdom
- **Top Product by Quantity:** PAPER CRAFT, LITTLE BIRDIE
- **Top Month by Sales:** November 2011

## Project Structure
```text
Ecommerce-Sales-Data-Analysis/
│
├── Ecommerce_Sales_Analysis.ipynb
└── README.md
```

## How to Run the Project
1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the notebook.
4. Run all cells to reproduce the analysis.

## Conclusion
This project demonstrates how Python-based data analysis can transform raw retail transaction data into meaningful business insights. The findings can help businesses understand customer demand, evaluate product performance, and support data-driven decisions.

## References
- Chen, D. (2015). [Online Retail Dataset](https://doi.org/10.24432/C5BW33). UCI Machine Learning Repository.
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
