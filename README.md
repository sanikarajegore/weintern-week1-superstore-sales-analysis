# Sample Superstore Sales Analysis

**WeIntern - Data Science Internship, Week 1**  
**Project:** Data cleaning, sales analysis, customer insights and visualization  
**Author:** Sanika Rajegore

## Project Overview

This project analyzes the Sample Superstore retail dataset using Python in Google Colab. The work covers dataset inspection and cleaning verification, calculation of business KPIs, product and regional sales analysis, customer insights, charts, and a consolidated sales dashboard.

## Objectives

- Inspect the dataset structure, column names and data types.
- Check for missing values and duplicate rows.
- Calculate key sales and profitability indicators.
- Identify high-performing product categories, regions and customer segments.
- Analyze customer purchasing patterns.
- Communicate the findings through charts, a dashboard and a written report.

## Dataset and Cleaning Summary

The cleaned dataset used for the reported analysis contains **8,399 rows and 21 columns**. The Colab verification output reported **0 missing values** and **0 fully duplicated rows**.

Keep the original dataset separate from the cleaned dataset. Do not overwrite the raw source file.

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

**Data validation note:** The segment-level customer counts sum to 989, while the overall unique-customer count is 795. This needs to be checked against the source CSV and notebook before the segment-level customer counts are used as mutually exclusive totals. Some earlier product and monthly-chart figures in the report were transcribed or visually read from screenshots and should be validated by rerunning the notebook.

## Visualizations

The project includes:

- Sales by product category bar chart.
- Monthly sales trend line chart.
- Sales contribution pie chart.
- Customer segment sales chart.
- One-page Sample Superstore sales dashboard with KPI summary.

## Tools and Libraries

- Python
- Google Colab / Jupyter Notebook
- Pandas
- Matplotlib

## Repository Structure

Use the following structure when organizing the GitHub repository:

```text
sample-superstore-sales-analysis/
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
│   └── Weltern_Week1_Data_Cleaning.ipynb
├── outputs/
│   ├── charts/
│   └── dashboard/
├── reports/
│   ├── Weltern_Sample_Superstore_Sales_Analysis_Report_Final.pdf
│   └── Weltern_Sample_Superstore_Sales_Analysis_Report_Final.docx
├── screenshots/
├── README.md
└── requirements.txt
```

Rename the notebook or report files in this structure if your saved filenames are different.

## How to Run

### In Google Colab

1. Upload or open the project notebook in Google Colab.
2. Upload the cleaned CSV dataset when prompted, or update the CSV path in the notebook to match your file location.
3. Run the notebook cells from top to bottom.
4. Review the printed cleaning checks, KPI values, observations and customer insights.
5. Run the chart and dashboard cells to regenerate the visual outputs.

### Locally

1. Install Python.
2. Install the libraries listed in `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the project notebook and make sure the CSV path points to the correct file in `data/cleaned/`.

## Project Deliverables

- Original and cleaned CSV datasets.
- Jupyter/Colab notebook.
- KPI and analysis outputs.
- Bar, line and pie charts.
- Sales dashboard image.
- Final project report in PDF and DOCX formats.
- README and requirements files.

## Notes

The numbers in this README reflect the Colab outputs shared during the project. Run the notebook against the final cleaned CSV before submission to confirm that all figures match the committed dataset and notebook.
