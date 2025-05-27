# Stats10X Builder Series

> Learn **Statistics** by building 10 hands-on, visual, and interactive projects inspired by key topics in foundational probability and statistics.

---

## About This Repo

This repository is my personal project to **master Statistics by building real, practical projects** aligned with core statistical ideas like probability, distributions, sampling, hypothesis testing, and more.

Instead of just reading or memorizing formulas, I’m simulating, visualizing, and applying statistical reasoning to concrete examples.

This is the **Statistics counterpart** to my [Project10X – The Backend Builder Series](https://github.com/eigenlambda123/Project10X-The-Backend-Builder-Series.git), and it follows the same project-driven learning approach I used for my [Linear Algebra 10X Builder Series](https://github.com/eigenlambda123/Linear-Algebra-10X-Builder-Series).

I designed this repo to be useful not only for myself but also for anyone who wants to learn statistics through hands-on projects and practical coding.

---

## My Goals (And Maybe Yours Too)

* Build strong statistical intuition through simulation and visualization
* Learn practical statistics concepts by implementing them from scratch
* Make abstract concepts tangible: sampling distributions, p-values, the Central Limit Theorem, and more
* Lay a solid foundation for data science, machine learning, and scientific computing
* Practice writing clean, reproducible code with a math-first mindset

---

## Projects Overview

| #  | Project                             | Key Concepts Covered                                                             |
| -- | ----------------------------------- | -------------------------------------------------------------------------------- |
| 1  | Descriptive Stats Analyzer          | Mean, median, mode, range, variance, standard deviation, IQR, Outliers Detection |
| 2  | Visualizing Distributions           | Histograms, KDE, boxplots, skewness, kurtosis                                    |
| 3  | Probability Simulator               | Classical probability, empirical probability, law of large numbers               |
| 4  | Dice & Coin Experiments             | Sample space, expected value, binomial distribution                              |
| 5  | Central Limit Theorem Playground    | Sampling distributions, CLT, normal approximation                                |
| 6  | Confidence Interval Builder         | Confidence intervals for mean and proportions                                    |
| 7  | Hypothesis Test Engine              | Null/alternative hypotheses, Type I/II errors, p-values                          |
| 8  | Correlation & Regression Visualizer | Pearson correlation, simple linear regression, residual plots                    |
| 9  | Chi-Square & ANOVA Tools            | Categorical data, chi-square test, one-way ANOVA                                 |
| 10 | Capstone: Mini Data Study           | Apply all concepts on a real dataset: EDA, inference, modeling                   |

---

## How I Use This Repo (And How You Can Too)

1. Pick a project based on the topic you're currently studying in statistics.
2. Read accompanying theory from your favorite stats book or course (OpenIntro, Khan Academy, etc.).
3. Work through the project scripts or notebooks, following the README and guided tasks.
4. Explore interactive features where available (like CLT sliders or p-value simulators).
5. Try the stretch goals to deepen your understanding.
6. Commit your notes and findings to build your own knowledge base.

---

## Tools & Libraries I Use

### Core Math & Data Libraries

| Tool       | Purpose                                                                                                                            |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **NumPy**  | Backbone for numerical operations (arrays, random number generation, stats functions). Essential for all statistical computations. |
| **Pandas** | Crucial for loading, cleaning, and exploring tabular datasets (CSV, Excel, etc.). Used in nearly every project.                    |
| **SciPy**  | Provides additional statistics functions (e.g., t-tests, chi-square, normal distributions) that complement NumPy.                  |

### Visualization

| Tool                            | Purpose                                                                                                                                   |
| ------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **Matplotlib**                  | Foundational plotting library for all kinds of statistical graphs: histograms, bar charts, scatterplots, etc.                             |
| **Seaborn**                     | Built on top of Matplotlib. Makes it easy to create beautiful statistical plots (e.g., box plots, violin plots, heatmaps). Great for EDA. |
| **Plotly / Bokeh** *(optional)* | Used for interactive charts, useful for exploring distributions or creating dashboards. Nice-to-have but not required.                    |

### Development Environment

| Tool                               | Purpose                                                                                                                              |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **Jupyter Notebooks / JupyterLab** | Ideal for this series — lets you combine code, visuals, and written insights in one place. Your default workflow.                    |
| **Python Scripts (.py)**           | Useful for modularizing utility functions (e.g., confidence interval calculator, hypothesis test engine). Keeps your codebase clean. |

### Interactivity (Stretch Tools)

| Tool                                | Purpose                                                                                                                             |
| ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| **ipywidgets**                      | Add sliders, dropdowns, and input fields in Jupyter for interactive simulations (e.g., change sample size and observe CI behavior). |
| **Streamlit / Gradio** *(optional)* | Frameworks for turning your notebook prototypes into simple web apps. Could be used in the Capstone.                                |

### Testing & Experimentation

| Tool                  | Purpose                                                                                                                                         |
| --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| **pytest / unittest** | Optional, but great if you want to test custom functions (like sampling simulators or p-value calculators). Helps practice clean coding habits. |

### Documentation & Publishing (Optional)

| Tool                      | Purpose                                                                                              |
| ------------------------- | ---------------------------------------------------------------------------------------------------- |
| **Obsidian / Markdown**   | Take structured notes as you go (definitions, formulas, logic for testing assumptions).              |
| **Jupyter Book / Quarto** | For publishing your notebooks as readable documentation, tutorials, or blog-style learning journals. |

---

## Recommended Starter Stack

I use and recommend starting with these:

* Python 3.10+
* Jupyter Notebook / JupyterLab
* NumPy
* Pandas
* Matplotlib
* Seaborn

Optional additions:

* `SciPy` for statistical functions
* `ipywidgets` for interactivity
* `pytest` for testing your logic
* `Plotly` for rich, interactive visuals

---

## Contributions & Feedback

This is my personal learning journey, but I welcome feedback, suggestions, and pull requests! If you create your own variation or improve a project, feel free to contribute.

---

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

*Made by RM Villa*
