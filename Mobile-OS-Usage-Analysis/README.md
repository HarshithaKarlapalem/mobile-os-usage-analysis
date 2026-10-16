# Mobile Operating System Usage Analysis

## Project Overview
This project explores historical mobile operating system usage data using Python. It compares usage percentages across operating systems and examines changes in Android and iOS usage over the available dated observations.

## Objectives
- Explore mobile operating system usage data.
- Compare average usage percentages across operating systems.
- Visualise Android and iOS usage trends.
- Identify data quality issues, including missing dates and duplicate records.

## Tools and Technologies
- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset contains three columns:
- `Date`
- `Mobile Operating System`
- `Percent of Usage`

The CSV contains 1,898 rows. Only 126 rows have valid dates, spanning December 2008 to April 2009. The remaining records have missing dates and require further investigation.

## Analysis Performed
1. Inspected dataset structure, data types, missing values and duplicate rows.
2. Converted the date column to datetime format.
3. Analysed the dated records separately.
4. Compared Android and iOS usage over time.
5. Calculated average, minimum and maximum usage for each operating system.
6. Created visualisations to communicate the findings.

## Key Findings
- SymbianOS had the highest average recorded usage among the dated observations, at 37.55%.
- iOS had the second-highest average, at 37.21%.
- iOS usage increased from 32.56% in December 2008 to 41.91% in April 2009.
- Android usage rose from 0.00% in December 2008 to 2.02% in April 2009.
- Missing dates and duplicate records require further investigation before analysing the full dataset.

## Project Structure
```text
Mobile-OS-Usage-Analysis/
├── data/
│   └── mobile_os_usage.csv
├── Notebooks/
│   └── mobile_os_usage_analysis.ipynb
├── Images/
│   ├── android_vs_ios_usage.png
│   └── top_10_mobile_os.png
├── requirements.txt
└── README.md
```

## Limitations
The dated data covers only December 2008 to April 2009. These findings describe the available historical sample and should not be interpreted as current market share. The undated records have not been fully investigated, and duplicate rows have not been automatically removed.

## Future Improvements
- Investigate the source and structure of the undated records.
- Verify duplicate records against the original dataset.
- Improve data quality checks and document cleaning decisions.
- Expand the analysis if reliable, dated observations become available.

## Author
Harshitha Karlapalem