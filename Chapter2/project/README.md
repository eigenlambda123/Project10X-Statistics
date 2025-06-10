# **Data Visualization Dashboard**

A Python-based CLI tool for exploring datasets visually. Designed for flexibility and ease of use, it allows users to load their own CSV files, choose a dataset to work with, and apply various univariate, bivariate, and heatmap visualizations — all through an interactive terminal interface.

---

## **Features**

### Load and manage datasets:

* Load multiple CSV datasets using Pandas.
* Assign custom names for easier reference.

### Univariate Visualizations:

Visualize individual columns using:

* **Histogram** with optional KDE curve
* **Box Plot** to view spread and outliers
* **Bar Chart** for categorical frequency counts

### Bivariate Visualizations:

Explore relationships between variables with:

* **Scatter Plot** with regression line
* **Scatter Plot with Hue** (color groupings by category)
* **Grouped Box Plot** to compare distributions across categories

### Heatmap Visualization:

* Generate a **correlation heatmap** using numerical columns only.
* Annotated and color-scaled for better interpretation.

### CLI-Based Workflow:

* Menu-driven interface to select datasets and visualizations interactively.
* Clear input prompts for columns and visualization types.
* Graceful error handling for invalid inputs or column mismatches.

---

## **Usage**

1. **Run the script:**

   ```bash
   python visual_data_explorer.py
   ```

2. **Interactive Options:**

   * Load a dataset by providing a file path and name.
   * List all available datasets.
   * Choose a dataset and select from:

     * Histogram
     * Box Plot
     * Bar Chart
     * Scatter Plot
     * Scatter Plot with Hue
     * Grouped Box Plot
     * Heatmap

3. **Provide Column Names:**

   * Input column names as prompted for each visualization.

---

## **Installation**

Requires Python 3.x. Install the dependencies via pip:

```bash
pip install pandas seaborn matplotlib
```

---

## **Notes**

* Columns must exist in the dataset; invalid inputs are handled with error messages.
* Visual plots require a graphical environment (e.g., Jupyter, VSCode, or a GUI-based Python IDE).
* Only numerical columns are used for heatmaps and scatter plots.
* For grouped box plots and scatter plots with hue:

  * Grouping/hue column must be categorical.
  * Value columns must be numerical.
