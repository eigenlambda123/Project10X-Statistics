# DescriptiveAnalyzer

A Python class for performing descriptive statistical analysis on CSV datasets. Designed to load data, compute key statistics, and identify outliers with an easy-to-use interface.

---

## Features

* Load CSV datasets using Pandas
* Compute descriptive statistics for specified columns:

  * Mean, Median, Mode
  * Variance, Standard Deviation
  * Range (Max - Min)
  * Interquartile Range (IQR) — inclusive and exclusive methods
* Detect outliers based on the IQR method (inclusive)
* Handles non-numeric data gracefully with clear messages
* Simple terminal output for quick insights

---

## Usage

1. Instantiate the `DescriptiveAnalyzer` class with:

   * Path to the CSV file
   * List of column names to analyze

2. Call `read_data()` to load the dataset

3. Use available methods to perform analysis, such as:

   * `get_mean()`, `get_median()`, `get_mode()`
   * `get_variance()`, `get_std()`, `get_range()`
   * `calculate_IQR_exclusive()`, `calculate_IQR_inclusive()`
   * `determine_outliers_iqr_inclusive()`

---

## Installation

* Requires Python 3.x
* Install dependencies via pip:

  ```bash
  pip install pandas numpy
  pip install pandas scipy
  
  ```

---

## Notes

* Make sure the columns specified exist in the dataset.
* Non-numeric columns will be skipped with warnings.
* The inclusive IQR method uses interpolation to calculate quartiles and detect outliers.
