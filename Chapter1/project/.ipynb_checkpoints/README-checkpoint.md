# DescriptiveStatsAnalyzer

A Python class for performing descriptive statistical analysis and visual exploration on CSV datasets. Designed to load data, compute key statistics, detect outliers, and provide visual summaries — all through a simple terminal interface.

---

## Features

* **Load CSV datasets** using Pandas
* **Compute descriptive statistics** for specified columns:

  * Mean, Median, Mode
  * Variance, Standard Deviation
  * Range (Max - Min)
  * Interquartile Range (IQR) — inclusive and exclusive methods
* **Detect outliers** using the IQR (inclusive method)
* **Visualizations** to enhance understanding:

  * Histogram with KDE line
  * Boxplot highlighting outliers
  * Group comparison plot (e.g., average by category)
* **Handles non-numeric data** gracefully with clear messages
* **Terminal-based CLI** for interactive analysis

---

## Usage

1. Instantiate the `DescriptiveAnalyzer` class with:

   * Path to the CSV file
   * List of column names to analyze

2. Call `read_data()` to load the dataset

3. Use available methods to perform analysis:

   * `get_mean()`, `get_median()`, `get_mode()`
   * `get_variance()`, `get_std()`, `get_range()`
   * `calculate_IQR_exclusive()`, `calculate_IQR_inclusive()`
   * `determine_outliers_iqr_inclusive()`

4. Use visualization methods:

   * `plot_histogram()`: View distribution shape with histogram + KDE
   * `plot_boxplot()`: Visualize spread and outliers
   * `plot_group_comparison()`: Compare group averages across a categorical variable

---

## Installation

Requires Python 3.x. Install dependencies via pip:

```bash
pip install pandas numpy scipy
pip install matplotlib seaborn
```

---

## Notes

* Ensure the columns specified exist in the dataset.
* Non-numeric columns are skipped with warnings.
* Visual plots require a graphical environment (e.g., Jupyter, VSCode, or GUI-based Python IDE).
* The inclusive IQR method uses percentile-based interpolation to detect outliers.
* For group comparisons, the first column should be **categorical**, the second should be **numeric**.

