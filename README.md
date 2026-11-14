# Sample Superstore Sales Analysis

**WeIntern – Data Science Internship, Week 1**  
**Project:** Data cleaning, sales analysis, customer insights and visualization  
**Author:** Sanika Rajegore

## Project Overview

This project analyzes the Sample Superstore retail dataset using Python in Google Colab. The work includes dataset inspection and cleaning checks, business KPI calculations, product and regional sales analysis, customer insights, visualizations, and a sales dashboard.

## Project Objectives

- Inspect the dataset structure, column names, data types and dimensions.
- Check for missing values and fully duplicated rows.
- Calculate key sales and profitability indicators.
- Identify high-performing product categories, regions and customer segments.
- Explore customer purchasing patterns.
- Communicate findings through charts, a dashboard and a written report.

## Dataset and Cleaning Summary

The cleaned dataset used for the reported analysis contains **8,399 rows and 21 columns**. The Google Colab verification output reported **0 missing values** and **0 fully duplicated rows**.

The cleaned CSV included in this repository is:

- `Cleaned_Sample_Superstore.csv`

**Note:** The original/raw CSV is not included in this repository. Keep the raw source dataset separately and do not overwrite it with the cleaned file.

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Sales | 14,915,600.82 |
| Total Profit | 1,521,767.98 |
| Unique Orders | 5,496 |
| Total Quantity Sold | 214,777 |
| Unique Customers | 795 |
| Profit Margin | 10.20% |
| Average Order Value | 2,713.90 |

## Main Findings

- Technology is the leading product category by sales and profit, with reported sales of 5,984,248.18 and profit of 886,313.52.
- The West region has the highest reported sales at 3,597,549.28.
- Ontario has the highest reported regional profit at 346,868.54.
- Corporate is the highest-sales customer segment, with sales of 5,498,904.88.
- Office Machines is the highest-sales sub-category, with sales of 2,168,697.14.
- Regular Air is the most-used shipping mode, with 4,541 unique orders.
- The Colab output reports 784 repeat customers out of 795 unique customers (98.62%).

**Data validation note:** The segment-level customer counts shown in the analysis sum to 989, while the overall unique-customer count is 795. Validate the segment grouping against the source CSV and notebook before treating those counts as mutually exclusive. Some product and monthly-chart figures in the report were transcribed or visually read from earlier screenshots; rerun the notebook to confirm them against the dataset before formal business use.

## Visualizations

The repository includes:

- `Sales_Contribution_Pie_Chart (1).png` – sales contribution by product category.
- `Superstore_Dashboard (1).png` – KPI summary, category sales, monthly trend, pie chart and customer-segment sales.

The analysis notebook also contains the code used for the visualizations.

## Tools and Libraries

- Python
- Google Colab / Jupyter Notebook
- Pandas
- Matplotlib
- IPython kernel (for running notebooks)

## Repository Contents

The files currently committed to the main branch are:

```text
weintern-week1-superstore-sales-analysis/
├── Cleaned_Sample_Superstore.csv
├── README.md
├── requirements.txt
├── WeIntern_Week1_Data_Cleaning.ipynb
├── Sales_Contribution_Pie_Chart (1).png
├── Superstore_Dashboard (1).png
└── Sample Superstore Sales Analysis Report Improved.pdf
```

The Word (.docx) version of the report and the original/raw CSV are not currently included.

## How to Run

### In Google Colab

1. Open `WeIntern_Week1_Data_Cleaning.ipynb` in Google Colab.
2. Upload `Cleaned_Sample_Superstore.csv` when prompted, or update the CSV path in the notebook to match the file location.
3. Run the notebook cells from top to bottom.
4. Review the cleaning checks, KPI values, observations and customer insights.
5. Run the chart and dashboard cells to regenerate the visual outputs.

### Locally

1. Install Python.
2. Download or clone this repository.
3. Install the libraries listed in `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the notebook and ensure the CSV path points to the downloaded cleaned dataset.

## Deliverables Included

- Cleaned CSV dataset.
- Google Colab/Jupyter notebook.
- Sales contribution pie chart.
- Sales dashboard image.
- Final project report in PDF format.
- README and requirements files.

