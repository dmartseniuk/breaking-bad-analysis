# Breaking Bad TV Show Data Analysis

## Project Overview

This project provides a detailed analysis of the "Breaking Bad" TV show, using data on episode ratings and duration. We explore trends, correlations, and other insights from the dataset through various visualizations and statistical methods. The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/varpit94/breaking-bad-tv-show-all-seasons-episodes-data).

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)
- [Contributing](#contributing)

## Installation

### Conda Environment

1. Clone this repository:
   ```
   git clone https://github.com/dmartseniuk/breaking-bad-analysis.git
   cd breaking-bad-analysis
   ```
2. Create the environment using conda:
   ```
   conda env create -f environment.yml
   ```
3. Activate the environment:
   ```
   conda activate breaking-bad-analysis
   ```

### (Optional) Requirements for pip users

If you'd prefer to use pip, you can install dependencies via:

```
pip install -r requirements.txt
```

### Note:

If you're running this notebook locally and don't have the necessary libraries installed, you may need to install pandas and matplotlib:

```
%pip install pandas
%pip install matplotlib
```

## Usage

1. Open the breaking_bad_analysis.ipynb notebook in Jupyter Notebook or any preferred editor.
2. Run the cells to see the data analysis and visualizations.
3. You can also modify the notebook to perform your own analysis.

## Analysis

The analysis includes:

- Descriptive statistics for episode durations and IMDB ratings
- Visualizations such as histograms, box plots, and scatter plots to show trends and correlations
- Comparison of ratings between seasons, highlighting top episodes and significant trends

## Contributing

If you'd like to contribute to this project, feel free to submit a pull request or open an issue.
