# Pandas Profiling Report

## Overview
This repository contains a comprehensive analysis of a dataset using the Pandas Profiling library. The report provides insights into the dataset's structure, statistics, and potential issues.

### Dataset Summary
- **Number of Variables**: 33
- **Number of Observations**: 569
- **Missing Cells**: 569 (3.0%)
- **Duplicate Rows**: 0 (0.0%)
- **Total Size in Memory**: 146.8 KiB

### Variable Types
- **Numeric Variables**: 31
- **Categorical Variables**: 1
- **Unsupported Variables**: 1

## Correlation Alerts
The report identifies several variables with high correlation, which may indicate redundancy:
- `radius_mean` is highly correlated with `perimeter_mean` and 12 other fields.
- `texture_mean` is highly correlated with `texture_worst`.

## Missing Values
- **`Unnamed: 32`**: Contains 100% missing values; requires cleaning or further analysis.

## Descriptive Statistics
Key statistics for notable variables include:
- **`radius_mean`**:
  - Distinct Values: 456
  - Mean: 14.13
  - Minimum: 6.98
  - Maximum: 28.11
  - Standard Deviation: 3.52

- **`texture_mean`**:
  - Distinct Values: 479
  - Mean: 19.29
  - Minimum: 9.71
  - Maximum: 39.28
  - Standard Deviation: 4.30

- **`perimeter_mean`**:
  - Distinct Values: 522
  - Mean: 91.97
  - Minimum: 43.79
  - Maximum: 188.5
  - Standard Deviation: 24.30

## Zeros and Unique Values
Certain variables contain zeros, such as:
- `concavity_mean`: 13 zeros (2.3%).

## Analysis Duration
The analysis was completed in **1 minute and 33.48 seconds** using **ydata-profiling version 4.1.2**.

## License
This project is licensed under the MIT License.
