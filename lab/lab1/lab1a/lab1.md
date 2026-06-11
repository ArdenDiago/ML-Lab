# Lab 1 — Data Preprocessing and Visualisation

## Overview

This lab focuses on understanding, cleaning, standardizing, and analyzing datasets before they are used for machine learning tasks. The objective is to evaluate dataset quality, resolve inconsistencies, handle missing information, and investigate AQI distributions using appropriate visualizations and preprocessing techniques.

---

# Task 1 — Dataset Inspection and Profiling

## Objective

Two CSV files are provided without documentation. Before any machine learning or analysis can begin, both datasets must be thoroughly inspected and profiled.

## Requirements

For each dataset:

* Analyze the dataset structure
* Identify the number of rows and columns
* Examine column names and data types
* Identify missing values
* Detect duplicate records
* Review summary statistics
* Inspect categorical values and possible inconsistencies

## Deliverables

* A structured data profile for each dataset
* A written observation describing any concerns or suspicious findings identified during inspection

---

# Task 2 — Missing Value Treatment

## Objective

The datasets contain missing values across multiple columns. A suitable treatment strategy must be designed and applied for each affected column.

## Requirements

For every column containing missing values:

* Decide whether to:

  * Remove the column
  * Remove affected rows
  * Impute missing values
* Justify why the chosen method is appropriate for that specific column

## Deliverables

* A markdown explanation of the treatment strategy for each column
* Null value counts before and after treatment to verify successful handling

---

# Task 3 — Data Cleaning and Standardization

## Objective

Both datasets will later be merged using the `State` column. However, inconsistencies in state names and duplicate records make reliable merging impossible in their current form.

## Requirements

* Identify all inconsistencies in state names
* Standardize naming formats across both datasets
* Remove redundant or duplicate records
* Ensure both datasets are ready for accurate merging

## Deliverables

* A documented list of all inconsistencies found
* Explanation of the fixes applied
* Record counts before and after duplicate removal

---

# Task 4 — AQI Distribution Analysis

## Objective

The pollution control board wants to understand:

1. Whether most cities are moderately polluted or if pollution is concentrated in a few cities
2. Whether the average AQI is being distorted by extreme values

## Requirements

* Investigate the distribution of AQI values
* Select suitable visualizations to analyze clustering and extreme values
* Justify why the chosen visualization(s) are appropriate
* Interpret the findings

## Deliverables

* Fully labelled visualizations with descriptive titles
* A written justification for the selected plot types
* Two observations directly addressing the board’s concerns

---

# Task 5 — Outlier Detection and Treatment

## Objective

Some AQI readings are suspected to be unrealistically high and may distort statistical analysis and machine learning models.

## Requirements

* Identify whether extreme values exist
* Quantify the number of affected values
* Select and justify an appropriate treatment strategy
* Apply the treatment method
* Demonstrate improvement in data quality

## Deliverables

* Explanation of the chosen outlier detection method
* Count of affected values and treatment applied
* Visual comparison of the dataset before and after treatment

---

# Submission Requirements

The final submission should include:

* Cleaned datasets
* All preprocessing steps
* Markdown explanations and justifications
* Visualizations with titles and labels
* Observations and conclusions for each task

---

# Conclusion

This lab demonstrates the importance of data preprocessing in real-world machine learning workflows. Proper inspection, cleaning, standardization, and analysis are essential to ensure reliable insights and accurate model performance.

---
