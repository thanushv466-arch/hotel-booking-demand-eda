# Hotel Booking Demand — Exploratory Data Analysis

A Python and Pandas exploratory data analysis project using a real-world Kaggle dataset. It explores hotel booking volume, missing data, cancellation behaviour, lead time, deposit type, market segment, average daily rates, special requests, and correlations.

## Dataset
- **Name:** Hotel Booking Demand
- **Kaggle source:** https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand
- **Expected size:** approximately 119,390 rows and 32 columns
- **Coverage:** bookings for a city hotel and a resort hotel in Portugal, with arrival dates from 2015 to 2017.
- **File required:** `hotel_bookings.csv`

Download the CSV from Kaggle. Do not commit the dataset to GitHub unless you have checked the dataset's licence and redistribution terms. The notebook links to the original source.

## Requirements
- Python 3.9+
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook or Google Colab

Install locally:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Run the notebook
1. Download `hotel_bookings.csv` from the Kaggle source above.
2. Put the CSV in the same directory as `Hotel_Booking_Demand_EDA.ipynb`, or upload it when prompted in Google Colab.
3. Open the notebook in Jupyter or upload it to Google Colab.
4. Run all cells from top to bottom.
5. Review the printed interpretations and add your own observations before submission.

## Project coverage
- Dataset shape, data types, memory usage, head and tail
- Numeric and categorical summaries
- Missing-value analysis and chart
- Duplicate and data-quality checks
- Eight visualisations with titles, axis labels, and computed interpretations
- Automatically generated key findings
- Notes on interpretation limits and non-causal relationships

## Important analytical note
This project is descriptive EDA. Observed differences and correlations do not prove causation. Missing values are reported before treatment, and the analysis documents assumptions used for derived fields.

## Suggested GitHub repository name
`hotel-booking-demand-eda`

## Suggested repository description
`Exploratory data analysis of hotel booking demand using Python, Pandas, NumPy, Matplotlib, and Seaborn. Includes data-quality checks, cancellation analysis, eight visualisations, and data-driven findings.`
